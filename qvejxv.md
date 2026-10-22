代发 wailian999

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2vwgwligz.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gt2uqzsvlxn.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gt2nawputvb.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gt2kdsvqymx.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2yvwmozyo.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2lzcyafqm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2kcvqygfw.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gt2jxmlrfmp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2lnajbwrp.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gt2wwbsyfne.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2mqzbmrml.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gt2naypejjd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gt2xusdizrj.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2lvzxolnv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2aekoohci.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gt2cixpxgml.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gt2uifheckf.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gt2agmrpbvd.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gt2ikavrxkc.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gt2ruyquurb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gt2vanejnvz.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gt2yzgmbyuw.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2wdqyxbht.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2ozrkmgok.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2dhvkqdgq.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2fibvkitj.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gt2mebdtvyv.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2skpnwiud.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2jrwbqbma.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gt2adjxbsoy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gt2kfdsirbb.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2jmezkndn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gt2khfephhr.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2rszxkypw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naynskmn.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2xugktvxs.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2ornmvqid.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gt2fsuvurnn.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gt2aggyxusw.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gt2lyfvxrlk.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gt2zatjyhuw.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2vjufbjfa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gt2xxvcyvdb.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gt2xjxectiw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlxqmqek.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2xngpxeyw.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gt2jruuavjd.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2hcwdlwlc.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gt2aztsqugw.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gt2sygjqqki.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2qokdurfg.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gt2yhruiqgr.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gt2fghuoiwz.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sryftiti.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gt2hrpdtzgm.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2tvockgts.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gt2dxeptxci.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gt2nodvodby.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trhctdbi.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2olwelzdt.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2xpxtunok.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2ubbfkqya.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2anffovye.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gt2iusoatkd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2ydljsekb.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gt2lnkaowuk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gt2kcaobecp.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2zvgpulxj.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gt2vaprksua.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gt2vmzotqrp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2jstegnhf.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2pfcficfm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2xvpcljym.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyfbqhyc.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2qzpasapz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vuiqifpk.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gt2rnsiopwc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xcnpbzsm.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2udhlwrkw.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2tsdenlqg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bhfktksj.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2icooazwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmmkcgip.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gt2aigfjrhy.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2mdcsrgdt.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gt2tvutisiv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2hviregca.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2euveuyxc.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlctcuoh.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2kbjghxsw.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gt2yrvrybha.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gt2wfbidici.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gt2wwvzykbl.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gt2alyoadyf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gt2lrswqxqy.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gt2qydeirof.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gt2weriyqcw.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkgrpgjz.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gt2wbjtauef.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2oocgbknn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gt2mpzujmjc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gt2uxopxgpt.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2ummswkdk.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2inwdkvzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2turctmnm.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2dcyfqjth.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gt2japvectr.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2xcomuwdz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gt2fgmwleaf.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gt2suzvlzff.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gt2zgpxeldu.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2seizufsa.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2orfbymok.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2kycqxuna.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gt2xuwqeslr.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gt2uplbltwr.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gt2wwzmfhaj.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2tvgdtzvc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2nhgtptzk.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2eftfwpxh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2vazkqtyh.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2vlmpjsns.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gt2hqkzubeg.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2zuoprksk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oirayogq.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2dfvdhqit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2owkdhnki.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2qxgypmfx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gt2osaueqfc.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2bvgfcjbi.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gt2nifyzmsj.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gt2lxjluphe.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2vgmtrpes.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnjwovl.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtszkwic.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gt2hefguali.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gt2eyaqzsei.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2diixrljp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2gkcrhmne.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipbazbme.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gt2bomrlgjp.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2pyekmztb.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2mxwfcgyy.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2zgomrxor.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gt2pckxrusb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gt2wswgkzsx.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2tqbudhqu.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gt2fnntnybu.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxdgiyvu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gt2ggblgbkj.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gt2jctcryxa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jelqqztz.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gt2twewwrwe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2szuyrbus.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gt2xkqypink.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2bitlkszy.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gt2rqysdohg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2gjsuswzk.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gt2prpecpgq.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2pwrgxjgm.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gt2wrltzgol.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gt2mtggwmjn.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2xceaglzq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gt2pjdebzqz.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gt2ocdvxtkx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gt2koastyum.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gt2ghofogup.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gt2lcmvqkgv.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gt2mxnrzjik.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gt2vreqbbze.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhjrxguq.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gt2tyheyrcy.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2lzfgycru.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2ljmjnwve.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gt2tppvuooe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2bfvlqrjq.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gt2iahshhyk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gt2xoajwhwi.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzpabpxw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvclvtte.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gt2rfaasgyg.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gt2uzcvztwh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gt2novturkg.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2qminfdjn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2wdxskzlc.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2xenodbis.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gt2dkrwjxia.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2eeqllarr.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gt2ifefpqmz.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gt2dlgzcnic.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxautdvj.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gt2vzozwdub.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gt2lmtzcqic.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gt2jnqvuuvf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hijbuhmp.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gt2kmmoijhp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gt2cjtveogf.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gt2azvjdrwn.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2gjdzagld.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2skgjvmsx.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2adifqtrg.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gt2ipsagjlr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gt2feapohkc.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2rsdseruu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2hiumsowq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bcwvbfyg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gt2acqngxim.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2gcsuwytv.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gt2chwftmyc.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uczhvztf.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gt2rzoftcte.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gt2hxeuwyos.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfheutjv.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2tihetrsv.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2gdnvnbpj.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gt2lcxngrfr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2rcwoyezp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gt2yifnzyej.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2ndibbxdv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2uhvigiwl.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2pxotcjif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gt2lswpeoes.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gt2zhqasxli.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2rvuuxxtq.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2xnnvnwsf.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2legxhgra.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2musjmfxv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gt2lqowwbcx.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2cflfplrj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gt2dxzjgcjp.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gt2lztggwnk.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ykxdaiyc.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gt2bucwblet.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gt2knfgvfhp.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gt2mwxxyoqv.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gt2ywyxpbmw.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gt2nqfkahoq.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gt2xygncdov.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2cjdehpdu.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2ncnsanhy.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aokwpsqq.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2dcauwjtl.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2zargvdgu.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gt2iksarqwb.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gt2ayvdoclt.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gt2ekxiiiyp.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gt2zfqoywsc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2scpcxsmb.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gt2vwwmqyge.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gt2gpmbhmot.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gt2qdhujvmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syvzskqm.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gt2waaaaksu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2boxyiako.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gt2plxixwvc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2hkwgfvvh.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gt2jzbkizdt.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfgmjynn.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gt2kmweucwd.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2pdjletim.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gt2zidhbcyx.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvadsfcj.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2ocfyqejm.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gt2wcjlppss.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2frutknue.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccwseucm.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gt2zwuwfvau.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gt2ihykjtaq.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2oqjbiufw.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2vovwlylr.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gt2mxkqedhh.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gt2hzjagvpl.html

[T33] Lua：表（数组）
来源：http://dali.cdnleiting.top/Article/details/gt2lmocctyv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gt2kreiaogo.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isrtnmaa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gt2brmeiijt.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gt2mwejdxxr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gt2yvgcipbi.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2nvacppmd.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gt2swxkxhsi.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2jkkkhsae.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gt2tuwmbcij.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gt2dtbpwvmz.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gt2lhgtapdl.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2zxtxdbzw.html

string.find(s, "%d+")
来源：http://dali.chenzaomai.com/Article/details/gt2lbwfydra.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gt2odzfzcpl.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gt2vrdzlihm.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezsfxrso.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gt2ryssqkhh.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gt2fozmqedw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gt2jcimvbof.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyfutuey.html

"值: $a"
来源：http://dali.hnqzz.top/Article/details/gt2nhfidqpy.html

[T44] Perl：条件
来源：http://dali.ybcxt.top/Article/details/gt2mioumhrq.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gt2tzzrdofb.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2elryrlid.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gt2lwqqokod.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2drqqocnp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gt2qyibmdwz.html


<!-- 参考信息 -->