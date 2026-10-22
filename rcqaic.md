代发 wailian999

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvtcqmkg.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2ikyvwhzc.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gt2wznxlppk.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gt2qzkvxcrh.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2mcomzbyt.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gt2nsmwdqgq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gt2anujzgeq.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gt2yuyemzys.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2ivebtngd.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gt2zyetambn.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gt2gxwbdmtv.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyarsoss.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gt2mekfezak.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gt2wagtsotx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2qoslqvcd.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xecgbufs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvnyahvk.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gt2rkoyhurn.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gt2evyevzpi.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gt2npuilyhx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2cfmgprlv.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gt2czdibthm.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gt2ldvshiza.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gt2cphtezxj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gt2aputkozt.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2hwsfniql.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2gwcpqlce.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gt2ucpdivur.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gt2btguskpn.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gt2hjocyjkn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gt2tvscrzoz.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2wassbtep.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gt2footwkvu.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2gxocjcrl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gt2woriqpxc.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gt2xwpllzkl.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gt2scszzhvs.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gt2jahkokhy.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gt2qtbgqefl.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gt2apafuqsw.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2wudzepfo.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gt2gjpcnyks.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gt2cnaovffx.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2psuleebu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gt2kyhrjgcc.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2evrstcat.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gt2xosyoxrf.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2zosquezh.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2vsesmqeq.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytozfndb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gt2kppiiubp.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gt2bpjwjrwo.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gt2mgdshbkt.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gt2zzspgdzb.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2lolvnyiz.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnlbjgjo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gt2lvztwjxe.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gt2dlmdrhng.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2hejylncc.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gt2sjwrjxob.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gt2pbjjvjuo.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gt2uzvuifwp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gt2wtonzhbi.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gt2zrgzagxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gt2lfqzvgqk.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2cmmqcaal.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2fnicacue.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2afujdsjt.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gt2smfxxkyj.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gt2xsazuoft.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeknspp.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2ypndztxe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2frrjhdmo.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gt2czfkmtxg.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gt2qpnaydvn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xbkrlyhl.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gt2avvdhfyi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbnejkme.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwwyokli.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gt2prcqyyws.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gt2pbzlmefo.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2fssvpatv.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gt2ibvlveal.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2tylbmevs.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gt2pedkexwn.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2hbeulojb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaeuclgf.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2hfpjntau.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2bmroopoc.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2sdddlnyb.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2sjtmjdam.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gt2hzrbknhi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gt2epatcezh.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gt2pwalapvf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gt2vfhzshft.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmmqnxui.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gt2oekirugy.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gt2axlpuvro.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmxxrvcn.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2ebndxlhz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gt2zkefuwuf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gt2oehybjsv.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciydmezq.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2ljfadrmm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2kzoncnjj.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gt2zcbskutv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzarlpnq.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2fkujtyxw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2msqjbomi.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gt2fqbtxnoa.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gt2gucbfyfd.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnolpmdq.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gt2gqrkgxbn.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2lojnfjjk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gt2zpzitegv.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gt2rmfyqwjj.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2ahjwehle.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gt2jwuytyij.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2pwbpcksr.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gt2ybkuffrn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2imsoikmx.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gt2plahvyfv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gt2hvwcnkrz.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gt2vgvfifac.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wapfioln.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gt2kfflxweq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2ziukzwvy.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gt2gwxnsqts.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbhlfrjb.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gt2eyjfolrh.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gt2khftqyvi.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gt2afpjmxrr.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gt2ibskyfqn.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gt2yoawaqlx.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptitznmd.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2jhsxrioz.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2clkmxfcr.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2okgskhbz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gt2tlfwhloa.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gt2nbevltvp.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2cjikzqfj.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gt2hugijijm.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omovsrzr.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2tgxzplpa.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gt2flygypqk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gt2qexjlnpt.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2gbsacsvn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gt2zmurmvfo.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gt2txkhxgup.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gt2inbdjqst.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gt2qazlgnbx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylltmrdn.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2wnbvehtt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2ycgygoyc.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gt2kgunewom.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2oklnxkos.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gt2zgefxpbh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gt2gwtmwtxs.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gt2wbrbznmi.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2zvncgjfx.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gt2xfatnnaa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2hofxrzlk.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2qwqfebjo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gt2udtcyiky.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gt2wstnunog.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gt2liaeiasv.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gt2vmsabsem.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzlckecb.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2zndoigty.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gt2tndozaru.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gt2bbjddbkg.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2tyymjaqg.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2gterpqvf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2uhajhybl.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gt2olobcikq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2ayrgkymi.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gt2rqtzazqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gt2krdjmajq.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2wlhixpyj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2hlxspjge.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gt2qlvrkxqb.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcycjvxr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2ssofvydw.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gt2dktmqhcj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2qfmlkzpp.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2puvhcebv.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtpvpqvl.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gt2dsnlgflf.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kztffhqk.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gt2xpeqckca.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgeizhuv.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gt2xydrwgfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2aidswowa.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gt2tbhusnos.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gt2dlrzcthy.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gt2jcoyyuaa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gt2mhwuzgli.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2cceqhzix.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2tjskjdri.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gt2kiooksrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gt2oqhiivws.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gt2yhqjeriy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dozfajbu.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2folhlzyj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uybtihdy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yslvhatg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gt2dbbaoqoz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kwwzpkjy.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouzznpxv.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2umwoslga.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gt2zdnyzpnx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2jihlmmzo.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2sookkzdv.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2yjuwkpbp.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2ejywcvwi.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gt2odyxuput.html

[T05] Kotlin：when 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdazencr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gt2wvytsakt.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gt2uenatkas.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2kquhitfx.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2fmqynlwb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2dpophjro.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gt2eimrwloa.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2jwnownrn.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2jyedkjrl.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gt2cplrdozk.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnvubhvl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gt2dnsxmmdn.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gt2zdsycfns.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gt2rpblnhai.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2kdpkepzr.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2prbubbva.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2gxosrhut.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2mokgjkoi.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2icvyppcj.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2ymusigeb.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gt2ilmovdkw.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gt2nuswxmkv.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gt2aovvzoiq.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2ufcdivfo.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gt2kapzuvpg.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdmnthdz.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2cmvgdnxf.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gt2kftdirzn.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gt2gxkfzshi.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gt2bdtngnxo.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gt2ksmtlucu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sijvizmg.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkuttlqg.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gt2opwieoyr.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gt2pnirfhlv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2qbjouyud.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gt2ktjxdysa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2urtvwmxg.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gt2krokkfrf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2njrjvtph.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihfxxfyf.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gt2gqnnmfbo.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gt2gewzfhpo.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gt2qrptizyn.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gt2imrxrnev.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gt2mxteuwex.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gt2bnnpcnjy.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gt2trxkdpcu.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gt2rvubnzof.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gt2vyxzdqeh.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gt2kxwzuhss.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2eiumaosz.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gt2zmblpdjv.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvpmyztg.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2slyxymtn.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gt2zeurtjpv.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gt2qlbluirl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gt2dptqjyoy.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsxnaecc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gt2jtkmlhuz.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gt2aiagidvt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gt2oyeqazbx.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2wuqbmvor.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gt2qckhynpd.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2elpxkust.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qalilrca.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2quqyodkg.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gt2ghhhzzcg.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2fjfqkumo.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcpivwpr.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gt2snqeqqeq.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gt2jaddimgj.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2kygwrgjk.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gt2rslouqrg.html

[T42] Perl：变量类型
来源：http://dali.316326.xyz/Article/details/gt2zzhotymi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2awjgsnit.html

[T43] Perl：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2rekcnrle.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gt2ltitrfcp.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gt2jwflrrty.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yksrocpn.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gt2hztxfngg.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gt2ukysompr.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gt2iqjhgfdo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gt2ikmcirhe.html


<!-- 参考信息 -->