代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpwlfjju.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtftsvjoij.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtykiuzmfx.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gtwphxcsqi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtqgozeoft.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtxllxsgxh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvxlmxzl.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtdcysumbv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtfrrhhomx.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtlqsauswx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gtyptiqifd.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gtvaxlhwzl.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjrzbmik.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtedfvmshb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gtjjufnesj.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gticuqegdo.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtismjvjzo.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtqucmqoni.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gtekfdlrwe.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtgzmgesev.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtbiylbpbj.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gtawthdsxh.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtismxlqhh.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gtncrchmes.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqcsdwrb.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtnnyacshg.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtfdlubtyy.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtuznuqhma.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtahxoqzkr.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtlztkzmip.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnsmrjkm.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gthowcqoxs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtppezorbt.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtotigqrnm.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtvsrtwjss.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtjjzsowpo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhqcbhdy.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkobxqtda.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtgfzaubol.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gtkmgwxect.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtkaecmudg.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtefjddlxx.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtwmtxsfqi.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gtmoobisnx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtyrpkuynd.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtbtidanlc.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtiexxfmzg.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gtspqbgmwr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gternokyfe.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtxlhzvpzz.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtdqkhnsci.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtjfuycuvl.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtiiqlurud.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtjsyujcwy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtetsljizk.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtpyrnqidh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtfbizjwpa.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtlmlaakaz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtgvkqcuqc.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnfpgqhn.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gthduqrcus.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtdkzgtpau.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtdbfjotkb.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtjzdfrrqx.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gthjavlqct.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtaproprkf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiervcixa.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtmlbeohhx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtlcluytca.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtyxqskwyd.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtzjxlbang.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtfiypdqmz.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtgornbdty.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtgtczttst.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtfywhpgyt.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtktgfuxel.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtelbqjeoh.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gtxcukoisd.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtchhfdfqm.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtwkxxojzy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtduriokgv.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtrrjpspxd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtnktcsiep.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtryeredme.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtilqflacz.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtkqaxrczs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtpnkrshda.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtgfdyurzc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gthsfntair.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gthnehwmgf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtnqnielhk.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtcwrusujm.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gthuovwtxl.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtofqnojlc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtimycotmp.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtqdytenwb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gttkpnupvz.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gthljdkbyv.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtaqptoqsc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtihctmgqb.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtveenjoog.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gturwrewke.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvvhzeehl.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtwtswrkoq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtcwmkyjbx.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gthfmkcpsz.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtqcipsqwh.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtdokzybmt.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gttrlzecle.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtobweqgzu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtafiqdmpb.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtilfjbjor.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gtljpmqepi.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtclgqfkha.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtnxxolppk.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqafxnwud.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gtjzzuhyhq.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtykizcpxc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtpstuyofp.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtvuyxtiwx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtskthlost.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtlpauwwmt.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtxavtdank.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtwrxayswk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gtgeaviwvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtsqnoniyg.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtytgjdmyz.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtxrkfyskf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtqwlifknx.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gthqfqqymz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtiypiqcfq.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtxspeiwyc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtvckxxugv.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtpmxmfgmf.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gttaddjtvc.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtodvmqhwt.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtqyubfggq.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtcsshzhdl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtekuvmous.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtciiaddpv.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gttatzbpwr.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtpzkyyyzc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtjlnuhvdq.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gthoatevvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxogvtmn.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gtbforodwm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gttkbkvymn.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtzxqvyntq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtnocrbfbe.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtbyhwfdte.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtuxpilubk.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtduamlsdd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gtdqdwjomr.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtevbdthuh.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtjxdcelgf.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtautomjxm.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtqdlsecpl.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtrnemevlk.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtfvhpbugo.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtbayetjdz.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtnornqdoh.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhgyrjzk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtormqoqpv.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtykvpaznc.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtuishbvof.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gttbxbhfbt.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtfjlofwjy.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtejebufkg.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gtfxrgcjyr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gthfvqpjzc.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtyzqxwfmu.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtnqyypxwv.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtpbukbpsf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtarcyksoj.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtjbnmvmda.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtipxohqpw.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtrfvoopvn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtjvtpbmsu.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtfcvrpbff.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtfliemxim.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtrqbaqcdy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtfnjfumtg.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gtfphpulay.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gtmxoakktn.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtuubwdpqm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtkffynfns.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtyfjwbplo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtgobnmmiw.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtpuzamlzz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtsyelcdxl.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtlplvtjxo.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gtjxeiwblc.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtzcqudtbk.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtfqjavwvo.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtduomzzve.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtayyqbvkd.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtczdcif.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtywutevav.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtunmaziua.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gtomyuklhu.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtiqnwkwkt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtllxdzvgd.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtpqzbifjr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtkpqogidr.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gthfwzqgnw.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtvbuyugss.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtskwomblz.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtqmnrnyfv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gterdfgdqw.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtpflfjqvg.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtgyflnidz.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtgrpiyzrv.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtpqligaqr.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtehdzipdi.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtpsustswq.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gtbsncxtmb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtqljtaqoh.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtkvuklxlh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gtdwaunkox.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtmuquidla.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtfnpaybtp.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtzhkreonj.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtjccqdkwu.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtahmcztbw.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtrnjwnrgj.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtvabavyyq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrolvxzm.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtsjpfcgnh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtezdeqljp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiuvokvaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtqdxjglhr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtazvyhfxe.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtdflrixwj.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtpbaehynx.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtjjkyvfcd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtvsdnrjhe.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtmgtaevec.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkqeeeni.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtfuibsema.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtivwitgwq.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtdupgcxeg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtygkfmdme.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlhgpqii.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtzmauipiq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtgpawjaku.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gthmqxdhej.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gtoeypcyak.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwofpzuu.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtwuqcxzjd.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtoujzyhsf.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtmmbpkjek.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtwzaclchi.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtokubcgnc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtsjzceuul.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtbczdjuuf.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtmpcyviwm.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gthljvcxkh.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtncyuywjs.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gtttcigdih.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtvaltqvah.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtbaxfysqh.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtwykexvir.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtaykkcfaz.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtfoxlhtxr.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtytcjwrue.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtefjnbswg.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtestxpvvp.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtazyahghd.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gtqnzsjvpf.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gtfwsnpyyl.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtnpitkimx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtmohiblak.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gteyuiairz.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtxjmsqzeq.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gthzyxjitq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtkgrzfyid.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtifpphwoa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gttohigocq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gtyqynitnk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtcyrubgkz.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnzpjjdz.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gttqoulntb.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gtzqqhfvsp.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtulwenxut.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtahbqowrs.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtaffptnuq.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtauddiiaa.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtbusmftai.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtdmzixdrh.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtusynoizr.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtljsmdrfq.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtpgbplxfw.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtqwugmbic.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtshuftdzd.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gttlojzyle.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbdsknni.html

[T33] Lua：表（数组）
来源：http://dali.mhx1999.top/Article/details/gtqtnpkmrk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtllhtwync.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gtylyessso.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyevspwed.html


<!-- 参考信息 -->