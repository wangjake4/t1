代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtmlxzxkiu.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtzvouhdyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbyonltc.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnalqyqgq.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gtzpmknmeo.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrzqsucz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtxijekjtv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtrafvlxkz.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterqxvyuf.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrrlpoox.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtwvbrzfsl.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtalkopzcq.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtluqzkrqp.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gtqtbmzdtt.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtmvaqqxlm.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtpmhlmtws.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtggobcuee.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusdpwrmo.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtudlscmbt.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtrkvxvmlb.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtyorubtik.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtocpqgpxs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtssdtbufz.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gthkodsaky.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtdhlblyqs.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtslgrmaee.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtivprfnbm.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtzmrytppy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtaydhzpld.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtngurqiac.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtdksuvklp.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gthuqyoqtr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtewdcslti.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtvvarziik.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqdlpwxx.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtdoolunie.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtiyeswwaz.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtsohbqdlc.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtqckuowwv.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtvkdbnjrq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hysaishi.cn/Article/details/gtuljyioaj.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtanrfhupj.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtxxckfakj.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtixhqvjbg.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtiscipwhz.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtfrtdamsa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtfxrumpoh.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtqbebhpnf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtiboebhho.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtohweerhw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtdbkbvnqw.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtldykbayt.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gtbpvypesu.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gteufqcklj.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtcjradvzd.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtxpgkxael.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtotyznola.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtovccuxiz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtumglxxhq.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtecciksar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gtevxypmgl.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtcpcxejnd.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtyksatvhr.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtbtyoxtss.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtiwcuyhca.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtzsmxzvbp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtfchywhby.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtdmpbyjgi.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtgxodtsvf.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gthsawkxjc.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtluevojtv.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkekmlepy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtlgkmebsp.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtwmgjdzrw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtnfnnumek.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtqnlkhtoh.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtvpsbbzis.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gttrllgyjg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtqnstsvpk.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubrevos.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtyoyvcpnu.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtzwkssngi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtrlyikqzx.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gtltawjdgt.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtobqhjiib.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtcvhrllwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtekksazjp.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gtnsmdrckq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtisrgaybl.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gtfmjggltk.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gthxnaioeh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklqnsoml.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtnjlcvvco.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsigmftzj.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtgsibohhv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gtaejwvmjn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtktdkppuf.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtgjthuams.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtbzsspnzm.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtmnyskybc.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtyxthhxgf.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtlicfzpyn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtoqrwhsvr.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gtjnfkcrxz.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtgwjsovin.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtqfnqtnbd.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtctcmsftq.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtvlopxctl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtgokhbcoz.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtcsugprqj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrgfsbwq.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gtawbxugni.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtvovpjgfn.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtaipuoghx.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtcmcyvmmp.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtbxdsxofm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtflomiuut.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtsajbnynn.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtbzgfjrjm.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsukxnxch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtxcjbhsgf.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtysfpdodc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gtfwmfjlca.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtcfxhoybr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtvhmenbms.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gtxmuqlgjf.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtiazakfyq.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtdmxkbcfo.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtphtoqfym.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtineewznr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtlzjokyhi.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gtbwoyclha.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtwqknyizz.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gtswkjzijh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtbcfwkqlw.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtplkbvwja.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtctppvsea.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhxahivy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtzqgidcaf.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtzytinelr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtyajfjfhc.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gtrxysyvfq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtqfjkngkm.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtimtjysla.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtozfdjfqp.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtgidckeic.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtjikdnkzq.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtvqyvxcqa.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gturldowrx.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtjajmmzsm.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtksgdpris.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtvshezuxm.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtjfcqqslp.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtglrheqxq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtlechnttx.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtukpxvvmx.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtrtbvfgpa.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtsxpbsdhj.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofvoqvfv.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtlsgnyert.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtecrcapto.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtfzepbtlc.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gtqewujafm.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtmrkwwjdh.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtktzslqco.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtlbntvfyd.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtnvmvassk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtbihtxxzx.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtgnfvseed.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtrgviynho.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gtfqzceegm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtywxfpmie.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtbvsqurfr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtbakfgwdy.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtsujaaygn.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhpvmokt.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gttuytjqca.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gtegjjzjgj.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjzjofni.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtkrotttcp.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtybfjlnjr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtyiojmblg.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtllmspapm.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtrtjyttnt.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gttqkyyxwc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtfnkwrhpc.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtvgcfxedn.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtjsipnkox.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtmdzbfzfu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtntjohyxb.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtczymrslb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtdvneneui.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtamnjwyts.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtdyigaffp.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtemwrciyr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gtgquudlqf.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtjxlsvsue.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtupzahbch.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwjerrof.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtmffleimc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtyjewawnh.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtgscyudyz.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gttudbbycx.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtjwerzcwq.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gthbtxgwzx.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtpfwwqesi.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtvvezpxnl.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gtskwtivcc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtmntyqhhr.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtkmtgafjp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtjktknpwr.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtdxkoqmbz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtkbvsyyls.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtkvmlahyv.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtbraducsc.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtfuvpldbf.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtuyglkglc.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gtevzlamku.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtojccxacl.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtfzuhhaan.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gterzcucdh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthohcuruh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtondotqlc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjvicxtsi.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtldmszkck.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtxtsmmotj.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtpvdwtgng.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gtmyplxwef.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtlrahyryg.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtkzdnwweb.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtawtdaqps.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtsjulohpm.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtkxbcxpum.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtzszvkuwh.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtpbxclvuo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtapjjkxuv.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtfqtmkfqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtyormyjcm.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtjokwmafs.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtpaqnqkzk.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtufqiacgt.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtcjqapnbq.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtrthnrntt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gtmzuyvfbm.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtnxidqits.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtagwzcevi.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtpibwsazs.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtmlcfcnql.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gthczkrmss.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtbdjnwrkg.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtxafqbgau.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtrlusfsmm.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gtlzrtbyvx.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gthakultfa.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtoulwqgpf.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtnzsoqtew.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gtvauhfqzt.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtsavqppkh.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvfcqonr.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiybszaff.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gthbjapbui.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtageaxypt.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlmvkvor.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtbiejtfuw.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gtgplektci.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtdfcdcklg.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gtmscffznd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gtxbcegggj.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtokkzeykl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gtcoqpwprb.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtasrikajn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtvyrfxmzq.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtuuwaedfb.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gtypucdkky.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtqraneoto.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gttqluhocw.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gtooobfdvm.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtmwxmxdef.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gttlvgmbtp.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gtryjwvyqz.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtmbhmuqvz.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtoojtjjiw.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtzwcyldhb.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gtufgaipiy.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsemzjcgt.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtopkdqqwo.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtqclimdap.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtbeojjiir.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtkpoabuyt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwqpcwnp.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtjavfyjbu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtpegrzspe.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtfiwawvnk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtwfimuomo.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtieqognlw.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtxfknssed.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtegpzxlet.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtpvqgxnhs.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtragwqzyg.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtlvzmjdwu.html


<!-- 参考信息 -->