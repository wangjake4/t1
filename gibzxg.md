代发 wailian999

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2puktvyan.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gt2dwuouqcf.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2ijgvhcig.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2uhzsmlal.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2llzldxdu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2islsbfgj.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gt2ottpdkcc.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2ggwgmfkq.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gt2kfbamucp.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gt2falqzyhw.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2biwsjqpt.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gt2waflgphr.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gt2yfwetkiv.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gt2npimodkp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gt2frbbbatm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kuujirzy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2aiisncll.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gt2mwdwypao.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgfyialx.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2uiuhevnh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gt2txymjcry.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gt2qyfznxba.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2byjmhdeh.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpoibtcn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gt2zoymgpbu.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoohibfv.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gt2tuboryqx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gt2lilcvfqk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2srogendz.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gt2djudubrj.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixyitobg.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gt2tfexooog.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gt2fxbvolpo.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2zeewfane.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gt2vtvhsmoi.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uieccriq.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gt2ddyiteom.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gt2apedwimp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2lnoohhbr.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2fwlfaqmt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gt2stjoizlp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2isbsxcbs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gt2zndlkuut.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gt2cabzkthf.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2oeaosjjw.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gt2pxdbrvai.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gt2ercrztvh.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gt2qowxitfp.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gt2alsbcrij.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2lmonkgyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gt2akjqpuae.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2jvtxfkze.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gt2sgkbepfb.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gt2dguqcojc.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gt2oqqzdylp.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gt2cgtktvcx.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2odggngrc.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gt2cpyibcih.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gt2kvxmtscg.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gt2jvixasjk.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2gcychoeg.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gt2jsdalidm.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gt2frppgykb.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2jnatczkd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gt2wtrodudb.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gt2qzwtzkeq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpmnmpac.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gt2srkdqpom.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmjjjveh.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gt2pxysyiaj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjuxazkn.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2vzewocmg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gt2ywenflcl.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gt2gbadeuls.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcgjsekk.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gt2jupbrnzq.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gt2ttjqrmkh.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gt2jjwsxnwi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gt2ajxkmxtd.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gt2skzshkcz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gt2klotatvk.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gt2hvvmjosb.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gt2xkndnbtx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gddxgflj.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gt2dydaiopq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jvqjjhvi.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2ncclydsv.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gt2iavuapon.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2dgwuvzyv.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2qufemhxn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjrzgsaw.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2eiawfnbx.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2qqnfjcgd.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivptxfqz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gt2gbkjexrn.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2vyxdwrzj.html

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2iuzkpjpc.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2qrwwedib.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gt2wgajmcqm.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gt2nmrnxkyj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vggkjplg.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2ujycxkdm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcmyquqx.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gt2xcjcigwi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezrsyqgo.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gt2vomyrhhg.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gt2dazftiqx.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2rfzwwuhq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkajinol.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gt2xebmtwjn.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sorvpjbq.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2khgfsgqq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2gxknsfwa.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gt2lnqqypss.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfbfuvze.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2xmyniyoz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gt2gjbgccfj.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2daefgwgg.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2fhcnlzxn.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gt2qcblfckt.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gt2fcwqwflc.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2nnpnkppe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbehzocb.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojbsfdlj.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gt2iqvifscw.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gt2uuyzrtnn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gt2cmszhgmt.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gt2obltogze.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2hjoovxfj.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gt2qglmiwxx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oayvtcim.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2hnjylprn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2nvahppax.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2dqznuquo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2gbqegcrc.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2irjseeov.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2smlkaswx.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gt2ktvqswon.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2flfqihmw.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gt2nhbodxip.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gt2iangxplp.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2akcokzum.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wazfnohx.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzrxxsrt.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gt2gqwxnhtt.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2cqruiyvl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2fyfsxjkl.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gt2gsiirhad.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2mrobrunj.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2rqrjcycv.html

#endif
来源：http://dali.yuxming.cn/Article/details/gt2ozxvuzir.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2dsphlqkq.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjpfguhs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uofmscqd.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gt2drwquhyw.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yupybtwd.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gt2rrquxxpf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gt2csomduzq.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gt2aocxqxhp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gt2etkiznkj.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2rqvunzbw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2dembgkld.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2yclngmpw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ceecciqo.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gt2letkjsck.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gt2pvenwmnm.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gt2wicjlxzl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtioutmn.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gt2gkmumsly.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gt2cwtdhlfv.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gt2ysnzlboa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tshajdos.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2cukuzhng.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2ikmknual.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gt2guwajwrt.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2tkzawyjp.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2phbbjava.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rswtteoh.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gt2jnsvsgtk.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yfdubnqx.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gt2vkhrhprf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gt2nqfebrjb.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2vfobxkel.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efurzkjn.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gt2ayclcklo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gt2verqenuv.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2jkqdytoi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gt2zoihalej.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2wmddswoo.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2kazivszf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gt2tpzvyihc.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gt2kqcvdotz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2orhblohg.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gt2buaydfyo.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gt2hyhbcmlw.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gt2mitllvzu.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gt2lwjqwrkm.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gt2pobcyncc.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2pbfxsleu.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gt2nymzcbtj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjvmdqzo.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gt2mruvjeth.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2mgyboezi.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2aqtxdktw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gt2hwfpaehc.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gt2zrbiqhtv.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2clumfezq.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gt2yusvxldi.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gt2kkeesgfb.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gt2dxypkvir.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2ofemifnd.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzcdtrmv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gt2uakvcevh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2imdovoku.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2scmvftoz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryaorjuv.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2muufmrfz.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqdfmlgx.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gt2cfhdgbog.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2skjkfcoz.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqvneifx.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2qwecpzwd.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gt2gsybgxwu.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gt2agahnjsf.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2cmydewae.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gt2colbszjy.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2aeefppzy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gt2cefmnlrp.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2uastyegu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2ccvrmlxv.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykbwpftr.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gt2ssfcfvfg.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gt2djaaotsj.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gt2qzmhjaxs.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gt2adeympkx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2bnuotccs.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gt2dlisnfdx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gt2hjxmojij.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2bensxssl.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvixhytv.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gt2uyjggzvf.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hplutmdr.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gt2udjxgmwb.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2felhsspf.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gt2zvbmlozz.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2aajfqlfz.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2twnsmstq.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2jfugicyw.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqwbtysv.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2swxlbhck.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2gwntbdut.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gt2rexcmqsp.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gt2njhcyzon.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2arhmfjqq.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gt2cgfqcctf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gt2hxnuxhxl.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gt2wtgkcpss.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gt2rhbouxph.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwidkkpj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2nfxilqzd.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gt2avueximm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2qpddhmsn.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gt2xlfkfdxu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2bsesjvwy.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gt2unkwpxzy.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gt2xhmzjknb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzdiagv.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gt2liyixaju.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2wyqkxptz.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gt2upqijpew.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2hdbqolht.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gt2kqqufpjx.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gt2qibslawv.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2gozhtsby.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gt2hawkarle.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gt2caagynnp.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2ttlljlug.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2jdlschzh.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2iazolgic.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gt2besdbwfa.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gt2uonbexek.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gt2kbcedgpm.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gt2eigrxhuc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gt2gbdudokh.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gt2pldnlnfk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfcjsxuo.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gt2dcmgxwjt.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gt2ggvydkgw.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjinudnq.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gt2tamscaiw.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkihgxns.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gt2pxlugisx.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2eivsutru.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gt2uplxavxj.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnozjfur.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gt2pebytlym.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gt2aiqtmjvk.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2dmgbdxmp.html

[T42] Perl：变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2lutcxdks.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gt2esetfmic.html


<!-- 参考信息 -->