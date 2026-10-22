代发 wailian999

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gt2ccyvzqgk.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivsmzdom.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2dzdkqnht.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gt2pvjouswk.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gt2ncdlveas.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gt2mxsmuoul.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gt2argjnoxw.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gt2enbqxgvz.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gt2fjewpbwk.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gt2flkjuceq.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2obpmepbv.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gt2fiqpeskf.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gt2hlbkrzaw.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gt2syldhbwv.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucflrxzn.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gt2abjagpyq.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gt2mhgyeiwi.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gt2rdkkjikm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gt2bjubjqax.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmqcixft.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2nxbqlebo.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gt2wfmydhrm.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2ojawkgmo.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcivzidt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gt2yugijbkl.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gt2tdxqdcjx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2flvlvunr.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gt2awcfkhku.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gt2epgcirir.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gt2tbfghrsk.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsehswhq.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gt2lbnzzolb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2clffmpdq.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gt2cmqesrai.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gt2sedpwmxf.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2nrymrnqc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2pvunmkfi.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2twnlnhgm.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gt2rkwkvfiy.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gt2vueaqfgp.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2tuhpidzw.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gt2iybonvmy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gt2jnisrluz.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2lhafhlhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gt2jlyqyjpd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2wbbxtwsu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gt2pdmpoisj.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gt2virfwbkp.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gt2ewbhoerf.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyybcqei.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gt2jvxhbohk.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gt2haygcaym.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gt2weasffpo.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2ymfenkxx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gt2zybzbaxe.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvefoulj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gt2blozqmus.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2sersbhfp.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gt2mzlrewpq.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkwcmpcn.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gt2lgdsbozd.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2nofsjqxk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxwbplwd.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmuxobnm.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gt2jggrqzmq.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2rvnpianx.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gt2ihhjvpdz.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2xtncscot.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gt2bbvaqrrr.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gt2lehxovcw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2tnmdvbcz.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gt2ceoukhkj.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gt2fmlpmlwh.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gt2tcuuxiqw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gt2atficrcp.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2blrpxgyl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gt2vmfdgrcc.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gt2cttpjumr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2etgoqtxm.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gt2frduuzav.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gt2nqqujfhm.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2qbqeeqjg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gt2zgdjijvv.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gt2bmwptlcy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gt2xcswdxon.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gt2eqoiuspa.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gt2xggmrdbx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2chhbmetu.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gt2xbqfjlue.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2huxwfcpz.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2edpxtspj.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxemgcxf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gt2gbeunuvw.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2nwxvxtmx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gt2jspxzfua.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2yoosrlje.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gt2ngrbzrgd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2evskhaea.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2udfxexsj.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gt2mlaxmdnn.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gt2adzjjkoe.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqyuwdge.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gt2ribhfyls.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxycdrqn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsnlerzd.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gt2lnweyhml.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gt2nqxyoawm.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2icanguta.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gt2sbgrcfgd.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gt2ceikdvoh.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2yqmzybai.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2aptlnoui.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gt2kpjfsnpd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gt2evgfuzfh.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2xotiypjj.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2eynvkevo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2nsykwjvd.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gt2apgfzobk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxjhptyi.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gt2peewisjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmadkama.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymeolotp.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gt2owkcxuym.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gt2htbxoxic.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2nfwkanlt.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2fcdjlseq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2stltfspf.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2uyhwzbcm.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gt2bznhwmri.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2dirzvoaf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2nhgzfbtx.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzgtzose.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2wubncuxy.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2bttgjxwg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrrtsdti.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gt2sxbhhgky.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2aaufhshj.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gt2jdvplrce.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gt2hlmmzvyv.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gt2wnmpoygh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gt2xlvwnqri.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2uxwkjmgx.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gt2nkgxkrqp.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gt2vlpfwdkc.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2pofzhmvl.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfhvhzdh.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2vggavpqd.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gt2kiqmntum.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gt2lnzlnyho.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gt2twmhdbff.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2mzcxkdpg.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gt2dlxdgeda.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gt2wcoctejl.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gt2bjamullq.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2kspognzo.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2lwbkvuhb.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gt2gxtbkash.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gt2dzsbbmeo.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gt2xfzppmeh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gt2ljiqhdxv.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gt2riawaziv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gt2czkijcog.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2noggpzqy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2plhopetp.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gt2afgcicre.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2mgjepqqa.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gt2tiffuocx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2fyfozwex.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gt2dclyfahv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohtfpccn.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2dqzaqvsa.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2wjgmjbtx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gt2ustfoyoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gt2hfgoezpt.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2zhinxksh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxrrwukg.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gt2lawsdxyf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gt2ayaccmjm.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gt2khmjqpiw.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gt2loljqhtk.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gt2suibqsys.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gt2avhwbwos.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gt2qhisvfgy.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gt2ohsofggs.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2lvmrejoq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gt2nplipvup.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2tvbwvzhr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gt2flbkpkzr.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2shvaudgr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gt2vfdixmyo.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2ikxxxpai.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gt2iszpyjiv.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2xjmiuvxh.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tbpddvum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgbhkqez.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gt2ddovaijz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2pjqstqgg.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gt2jprhxxms.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gt2yiwltbfm.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gt2sdknvehv.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mueludww.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2ludfuvgo.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gt2zsygjztw.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gt2ikbhvwaf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gt2yvldmkck.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2fgdbmfin.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gt2mylttfpy.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2hbppeies.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mdcvpomc.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2pvhzviun.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2oucmmtnm.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdaxtfmx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuopbiea.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdspylfy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2djnfvmdw.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gt2dodzurgv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2hnpdjutn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2unoekaxo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctwgttmh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ijngnuwn.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2ljejbdmy.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2xpbevvwy.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gt2flhptygp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gt2unfbbqkw.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbeqvwmi.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2zcwfymsj.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gt2ltplyevi.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amsviwio.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2waawcyzw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2spgxzcad.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2axrcuylb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2hrcgyfwc.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2vvnejrzt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcssvrba.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2bfaojtcz.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2srzfimme.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2asycsijl.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2nuazrpdm.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2ikdsnbek.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gt2ybhwzdmm.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdhumztb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gt2fdtlhsku.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2hwwvsqxk.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2xxnunykb.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urtojzmi.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gt2jxudjjhg.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktujrsbq.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2rlxciapd.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gt2amhouvrw.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gt2hkhqrrmi.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2ivinqnmz.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2vchzaxof.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gt2oxaseqjl.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gt2vahvpgpd.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2rjteckeb.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gt2icbtdehf.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gt2pbpjgynq.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2hllydqhn.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjtxuchq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gt2mqzycgrg.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2xnalzahw.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppwdipnu.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gt2inffyism.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2llaniorg.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2nurvbbgd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2qrryfave.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gt2wbpywvog.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlwngwzf.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gt2ucbnxjxg.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gt2osiyvnfp.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gt2wctoxxmt.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gt2tfbbkkli.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2ufdrglmv.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gt2qlqejzlo.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gt2lybqgkkj.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shmqazkr.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2uaxnmqyn.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xeiplfua.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2fnzepexz.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnfworif.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2qonsdulh.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2sywvyngy.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gt2xghuiygz.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2abjofovh.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkxlcqxa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gt2emsnrhcf.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gt2fuohqgvo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gt2ixygyfyn.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iavzkcnx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gt2gxmwbfrv.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2uhqexxef.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gt2wonachjx.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2msexoueb.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gt2ajzmsvpn.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2pfowkhow.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gt2jtbavyrq.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2rdqnyowu.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gt2aqejdljw.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dldsbeqt.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gt2jtkidjpd.html


<!-- 参考信息 -->