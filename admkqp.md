代发 wailian999

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2epvlddhv.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gt2adalkgms.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gt2ffeghxng.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gt2dlsfrdvt.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2zvsnfosz.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gt2ucqjefaa.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2awdbuoap.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gt2rvmkztuv.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gt2xbqzerzk.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2qdyumopm.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2epadxdsk.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gt2wfuehkzh.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gt2uspfcokq.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gt2rnlwvdsr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2cfhqkwub.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gt2qhvkpxjs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2amfkxewb.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2gluuezyy.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2dvyrpatp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghspdnpk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gt2marsgyiy.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwqurxfe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2ajkzjjfe.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gt2qdulqfia.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gt2bbaudmso.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gt2advmbxnz.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gt2xddazixw.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gt2yknyaryz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gt2qquvcxch.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2nacvjbcj.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gt2ommpisqk.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gt2qqsxkuvz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gt2zzzybnot.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2bavvcywb.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2kmasyzxw.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gt2txxybpwr.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gt2zzvoybds.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2vjkgruyt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwcvtvmu.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvzginfq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gt2cczzfpyz.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2sdiweqqa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqkzisgl.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gt2jcyrgifa.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gt2cjqevorr.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2lkvskwcj.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2zgueybbk.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2pzuuxlkr.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2jstiylgj.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gt2hluhuiqw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2oamodqjw.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gt2ktkqlvlo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gt2wqkhkfbf.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2aocywhuy.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gt2pstllgry.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2ajtulgnf.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2fkipnhxc.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpqioncv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enaylzxd.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gt2wyisippd.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gt2zgogecde.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gt2tgfzpcoz.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gt2ewunskvn.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2zmfgsllw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gt2oxpkduhd.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gt2uismozno.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2ezjeyyys.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gt2ktykkmge.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gt2lktqhyyw.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2ehyvuluw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2mgsflmvm.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gt2cdnsaulm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2swlggdzd.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gt2bwpeyako.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2jdnulxio.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gt2zhmtcfvi.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2gdlbfygh.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2xathrkir.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2gztbjhqx.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gt2txcongfh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gt2eekihydx.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gt2ettwtmss.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mltqxgxr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2lmdkcetv.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gt2dafnzcnm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dckkpiih.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2csuorhlh.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gt2tjpxioin.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mhorcpsh.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gt2txwtwacd.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gt2nozmnide.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxgmzvlt.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2yjlosenv.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2nqqovxju.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2nczvwdam.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2pdtrpwdp.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gt2dadkfjqf.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2edqtluul.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gt2utccoeqv.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnsepyto.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gt2prlpnqxo.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gt2grjzotyz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2vijypcxx.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzcghtqk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gt2bcmxdnlw.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gt2kpxuhxfq.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gt2wdhepzmb.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2dqqkyphb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqdwcqjy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2kkdwlqli.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2nucejgut.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gt2ubmpnzwg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2gvjdizfp.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2noxwlsrx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gt2whccdpdg.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2mmmrwezu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gt2havrvuyl.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2zkhwstdb.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gt2ffeiadpw.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gt2mzuthvaq.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2tvzioyig.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2zvvndkyg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gt2sahjalkm.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gt2nekdncux.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2jmcmcvxx.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gt2czsxmjui.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2ahhxnqau.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gt2mjpcepsk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2nfaiuntg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqivzje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gt2kyigoclz.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2nlmcswab.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2lcxyzndk.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2pdiekzdg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gt2kkajuxzj.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkrgidmj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2jjbrpted.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeuybkuu.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gt2gecehuvd.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxateveo.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2tujtrtwu.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gt2iibtzmqn.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2hzukddxk.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gt2stmudsva.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gt2yhanebph.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2tppjzvsf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfsuuysv.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gt2nkrvshub.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gt2lclvjwiq.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gt2owhfpsrr.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2vodvbrtx.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2xwuomcle.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2wwednjjc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gt2yicwwkzf.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2pyjsaeit.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gt2mnujreka.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gt2pfeawvex.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aanqfwkg.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gt2rbbfljqq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gt2yrbuerrh.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gt2xchmogcc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2zbtcbxun.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2rjbfxxfn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2ohutvreb.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2bjqumyow.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gt2bcfhuqrf.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gt2ybcgtttx.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2jccgbmxz.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2pohfkxqd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gt2uqeuowse.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gt2ipvgtsrv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2vdenxxbz.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmwutpox.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gt2sdwungac.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miyabgan.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gt2ekiqovkd.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gt2fyurxnct.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2ffbkeqsf.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2gznmvgea.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gt2qfidjwfn.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gt2xemkdtfw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kypsbiqk.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gt2zxsorgyk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2qqvxglcf.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gt2aqdudbyw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gt2zsbalnav.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlxqmszo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gt2txrbpalj.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2pyustjvt.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2bgqmsbus.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gt2rfqfvyue.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gt2botqblxs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2fmurbgqs.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gt2eiukcmmv.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gt2grwotmwm.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gt2juqxiejy.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gt2odixjdfv.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gt2rlwqylrt.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gt2njlflmtb.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2ondzisxb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gt2zyrvrcys.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gt2vcdrkaxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2jnsyqenh.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xswtntcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gt2qhfpeddp.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2nmprarhz.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2nrcinuaf.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gt2ogglfzjq.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gt2mzwvwvlz.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gt2lmpajvmw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtrfgtnb.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2kbxpdcjc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2dntlnvjw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bkaqcqkp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2pbeurzcw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2acivtkmo.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2opzrnove.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2enkuyzfi.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gt2uqvdlzdx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gt2hymatpjr.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctwhaakz.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2stosnnov.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gt2ztshzkjb.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gt2wzwbupqc.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gt2bzqvflrl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oysbpxvw.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2bstglnpg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2rsaohgen.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2enlyojjl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gt2ppiubjat.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2nothoeuv.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2bcouiaee.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2huteumre.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gt2jxmdivaf.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gt2molirfpk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2cimnidhp.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gt2voxlisit.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gt2hwkfiiyb.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gt2cpykwiux.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2yldthjji.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gt2bseofgky.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gt2sujdhrao.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gt2afxotkri.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2kbmifiyg.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gt2cotfqsga.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gt2mflznsjb.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2tcrlitrg.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2bfpmhtgw.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gt2qfldufxr.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gt2wxqptvnm.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2pjcjfuoc.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gt2whyieybe.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gt2zwxxbpty.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gt2abkripmm.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khooorco.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gt2nnddlysv.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gt2ddxonsga.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gt2fsqpkjff.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gt2oqtqphbm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2penfcowm.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gt2svjdjycg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gt2ictjqeay.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2udnugnon.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2wrztgcks.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gt2euzkwcof.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gt2dnpbjwkw.html

[T26] Swift：类与重写
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmxtnmao.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onqytbva.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gt2tevmxady.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gt2snpzvfne.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gt2dtzqoesw.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gt2hstopowc.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2eiuqvodo.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gt2yqqtnhus.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gt2johvaowf.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gt2obofyjbe.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2xpramssb.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2vsnbceem.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gt2xhpxuqmy.html

local a = 1
来源：http://dali.316326.xyz/Article/details/gt2btfzwjmg.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kleskisv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gt2hyjfxknk.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gt2dzzlqmmd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnyfwotj.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gt2mjfsgnmt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2yhhwzzbg.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gt2yiwxdqhp.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2foqhjclz.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyrknbbp.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gt2lngrwjzm.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gt2ajgrhoij.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gt2xnpyzibv.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2offdqysw.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gt2cdpmlwbj.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gt2vqibzttp.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gt2txgirivj.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gt2dnezjksc.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjcciemb.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubfabyja.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2wpqlazvr.html


<!-- 参考信息 -->