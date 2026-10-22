代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgufenzy.top/Article/details/gtuftljvyc.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gtjfvphkxt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtrqsbnktk.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtdysnffpy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtgjecldhv.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gtuudzxfbx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gtjozjfegp.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrduiygd.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtpwcjzvae.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtkfzjktcj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gteujqgzmz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwqylutw.html

cmd > out.log 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrphvtnn.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gticrfcbgq.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtbxyohlsp.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtqljzcnoy.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtkcjzxarc.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtzabmuqfy.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtkjyyzhkd.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtrymgsjze.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtkqmvhbhw.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtsebwonvz.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gtnarcknll.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtqinevwwc.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtzxubksqr.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtagvbxpya.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gtsettrdrm.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gtmvsgmcfz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtbfjwctjw.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtwpyvpcbb.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtethpzgqx.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtinalcyae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtzetbrplv.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqphfkmut.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtflpsvdhi.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtcixevneh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtexfkfjgt.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymjizoro.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtkynbumkh.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtppxozovh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gtxidiuyon.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtkkbpoxhi.html

diff a.txt b.txt
来源：http://dali.jyoumei.cn/Article/details/gtroyycdoc.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtxqdppbvm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtrwlwtruk.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtokzcjjua.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtqwljhouz.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gthghrjdhh.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gtycogxtur.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckpanmtr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gtsnrokuhi.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtlxcamswk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gtuhhfyzee.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtuxhdxvpg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtmiqwfrwz.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gthtbqbnww.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gtjhxwjvsq.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtzhflsvnb.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtsacfkqgu.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtqjmiqwqc.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvemrrhrw.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtjthgcfhv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtwaaxrnry.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtzbttmixx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtfybwrtkw.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtheeehfql.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtiulfquvn.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtoohgzgxy.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtuhfduabu.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtepvqbzjo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtbnesdqzq.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtizxhfobc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtauyyshxx.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gttzvnpnew.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtotsfbcvi.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtvbgfejgr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtkeqmekcw.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtgzzvmdwv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtnnokdbrh.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtktsjimju.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtuwmfcfww.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtphiovspj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtapcrquzw.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzutktdbs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtsrsoknzb.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtrserghbt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtbjamlcbs.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtrzjbbrbn.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtbazycbcf.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtojoigboq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtmzbmclfl.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtwaawbuqe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsslhernu.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtjbjfzdbu.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtzozcjvua.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdsedytrh.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gttetaarfz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmjqadego.html

[S01] C：Hello World
来源：http://dali.cucudq.cn/Article/details/gtzrnmtstm.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtnqanjqvi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtoqxczoem.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtwbcjdnqt.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gthhsrsihk.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtobigfagr.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtfeniwlcq.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtjdwwyris.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtuvjogezq.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gthvrpaodx.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtkarcuwxg.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtgyzknmut.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtofwlmdnn.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtwkclxztt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gtyrunefyc.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtzhahjxll.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtoqsmwfza.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtmqvpxnel.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtrbkvlojt.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtxrccoqik.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtbgbjvfnl.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtqsxcgasy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkazyucgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtynmnkirl.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtqnmdgwcb.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgsyiiey.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtsfjnkyaj.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtpntgswhn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtovgpblhz.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtthnpyavt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtyulyatja.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtdmxkqylv.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrupfynol.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtewbpgtrd.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtoctcsgww.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtlihvuocy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gtwxizxvzj.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtvukzhrpr.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtfrksmcxl.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gtrhfrhqyv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtvdklatrb.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtostqbdsv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtlldfvfaw.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtcavriwrf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtkaddegfz.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtkcijkijp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtrfbmsrfr.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzqxycfp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtsnkrxdvf.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtgnklcqii.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gttyynctkn.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtgvsuojks.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtkxlsbfmh.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtxwjmsyut.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtghgzsfmq.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtjlnfshaw.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtnxtckldz.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtkuezmavm.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisyqeipx.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtjxupmjyn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtwzuvubgw.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtqbzjsvvs.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtercqnahh.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtwwnlgebf.html

#endif
来源：http://dali.hnqzz.top/Article/details/gtnrngawvy.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtziqotdwk.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gtgqfkblya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtbwiqtexq.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtkkukwomc.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtoazmmqeb.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtwegsizqh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtqjrbldeq.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtekulpqsz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtkqrryokf.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtsqhcekdx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqinwdooq.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gtdggeexyw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gttkalxifn.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gtrvurdxci.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtenelzxqb.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtojpfqyos.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtjkzynyvw.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtzeelcfbf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtqlgswmrb.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtuagefeyl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtyywvkyle.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtmdbovxno.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtfqsviwhu.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gthuihfmcn.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtqnkuphza.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gtcygtskjq.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gteivqkyzt.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtwvydewzk.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gtcvemsccb.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtzinccdcr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtcrkajzkb.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtffntdhjo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtlhuzxcxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtyafctlkb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtqhzgyehp.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtpsgwesoz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtgwyzdupu.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtsxcqvucb.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtvlxlyczv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzfeinij.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtwhyfokzw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtgdwigybn.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtkodahdnt.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtlilonsua.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gttblprsjo.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtifgbmeab.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gthqiyquqk.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtkhuolpgi.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gtbdsvbqun.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gtxpxjddmg.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtolxwdjai.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtjaqktwfp.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtzcnqpsvg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtethfupzd.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gthfyhualt.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtemmhgigc.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtzmtoclwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtksxycasp.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtqpqmgqku.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtxpntbtse.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtcmjtljnu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtrxoxybuf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzlanhliz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtpqcvdywe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtinuepotk.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gthfifzpby.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtzxptxyer.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtqwcxhkxd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtozlrhzcs.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gtohuxjoxu.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtzmgvaajs.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gthdqxcxtz.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtpisqlpwx.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gteazcvzts.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtlbucblik.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtufibqphh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtzfopokus.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtvxnkgrxm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gtfqvnfstd.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtbmfuqokx.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtaannxgig.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtkwjwlytz.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtagjywvxw.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtidilhuij.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtxojihexl.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtxjoeegrs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtnawjrtbk.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtimhjuhan.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtkbbhxjpa.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtmyhijicc.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtytelhbew.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtotdeyqmd.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtlpljptdg.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtpogbxgqf.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtohfzqdul.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtjvtlpdih.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtygdyjnri.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gtehruqdbq.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtrlhovbjk.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gttznlfgln.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtwrtftpmb.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifcttfon.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gtpllaehch.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtkoggucak.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtbomwqmfy.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gticeofitc.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtkklnchdd.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gtwjwqpvjj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtuzjcuqfs.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gtessjetmn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtljubghhg.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtplpmgxxi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtxhdgdzuk.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtzdybtmux.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtztcqegek.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtnzgmcszb.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtflwdxbei.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtuzpdyysz.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtldeqrror.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfduerhwl.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gtodctyeef.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtzorlfrjd.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gtlzilmakb.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxghjlpx.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtlryazoym.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtlunuvqpr.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtcuodbetp.html

[T32] Lua：局部变量
来源：http://dali.yj20258888.top/Article/details/gtxlnbfvkm.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtrwpeaooy.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcvigfng.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shangyingyoupin.top/Article/details/gtpxuzjgnm.html

[T34] Lua：遍历表
来源：http://dali.zhiwuduotai.top/Article/details/gtwsrlbgck.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtaupvxxgl.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtepzknhmv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtsinzewds.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gttxxqjueq.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtehralswy.html


<!-- 参考信息 -->