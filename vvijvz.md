代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtjazzltjd.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gtsthvlnnn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtxfdkbfbl.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtcljfeedb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtfpcjfcdu.html

[R36] 并发执行多个任务
来源：http://dali.birdmap.top/Article/details/gtvxpclffg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtkfvcswxn.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gtnabefrut.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtbpqnltir.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtknqluddl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gtdgurrxyg.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtyapyinar.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtkmpatvhz.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtzaisvxrz.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtxgizdzqw.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtsxvaawke.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtdyazfaaz.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtdcizasmd.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtnqszflwx.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gthyxxepep.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtnuhcxlyc.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtahsbsanr.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtmnwqvmlq.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gtwykiujmu.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtusoqeehe.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gthgrbvaqf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtzmgtbxyu.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtfaepvqgs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtmqdkuvhz.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtnlxcvvrn.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtufzxjtmi.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtxecyggiq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gthuanntun.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkkucvra.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gteegmeqfc.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtyyurbrkt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtmcdyipqj.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gtnrbgpykb.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtbbqefxcp.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtixlgkgqa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gticmirybp.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtzobdylsl.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtgofykhyu.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtskgywcnx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtlwwhbvtq.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtwtfvtdss.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtlnioolzm.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtkcaweaxk.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtadisinnn.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthbbhqmyw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gtpgtwgizx.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtdjxyzuar.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtnulqgjvh.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtovdwlswo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtwtxesnog.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gtxdeshoxx.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtwgitqkaw.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtaisthams.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtjrzikyqi.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gthmllutal.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtdizosull.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtzjwbznvl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtxbgtqdfs.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtmkpicczw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtqhyfwlwd.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gtknkabeuf.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtibhbdntb.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtvdixakmr.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtulzpdpuo.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtmcgynena.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtpbajbvis.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtdoprsqns.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtbyascfcr.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtxqswtnhi.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtcjgnwslq.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtqgiglevi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtskeznpaa.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcujfnjqc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtxuwfvefd.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtoakzrjcv.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtgblqmxuz.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gtnwvmrpjm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtnafqaljp.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtcaifqnxe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtywubcjii.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gtuslkuxfm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtpylnzxnp.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtjjsjrgmn.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtfuogdydi.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gtydbssxhq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtgaqajwjd.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtkevhikug.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gttvenxeoj.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtzljmifaw.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtkbuxwgar.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjnikmcvp.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gtnlayuuhb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdgxhdame.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtscpzlmzb.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gtyralqgjv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtszvxgbbf.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtcourlrww.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gtacvetkwb.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtcuposkmt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtbygfyknq.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtahbgigix.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtkwcxchov.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtpqxgdwdx.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcjqjken.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gtjcggxmej.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtgcjjwlkz.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtovfujrza.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gttkvweath.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtptrryfvc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtcbuagzjw.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gtmidkbxmp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtskmwsfgl.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gtjvfjdahg.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtsbfmtngt.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtcqpczyho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtcbixsyeh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtcbomiqif.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtmtpomanw.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtsrgphbto.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtltzpfaco.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtknlbzppd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtrzyxeldb.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtsauoogyn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtlmbtczcq.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtrkwlwjzz.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazibfvid.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtlpdcbcmu.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtarndyeka.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtylzcklag.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtdluhgvpo.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtqozezkeg.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtsrcxeayd.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gtfvoyehub.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtmxdqlgko.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtuvmeezkf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gttlwokgih.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtdktfrwhg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtolgwgqrq.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtldstdraf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtgshvwzao.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtvavbtqpy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvekpsdik.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtnkpxhzhn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtjqiffplu.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gteeplzkvs.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtvfbzlwst.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtythguyir.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtbxtewdwb.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtjuxlalbg.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtzegxzvjs.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtvadlmcxf.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gthenfqofi.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gtuorgmgzx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtwdnerawy.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gtdoadhpao.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gtqnqjhxpq.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibqirseh.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtytfnynuo.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtqepusaci.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtpxvhbaxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtrkugrzpq.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gtrmkowxml.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtbyxkljmg.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhhwcwaw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtpspfgcyf.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkylxamvd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtkxltsvuf.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtpfceoeif.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtgbkpuxed.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtexmzgnia.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gttufxmfei.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gtckqpjuqc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtpyrdowhc.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtucaxlfla.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtcmvttsij.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtaustcjkf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqzuvdsx.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtkjhitsci.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gtithbklcs.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtgfncmzup.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtkkhqidhh.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtnfqefsfp.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gthlzanfcm.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdalhbklj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtvpigjcoy.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtkpophkpj.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gtdmfbpxhj.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtdlziqnly.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtkhhwnlvi.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtmgiglxzj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gthofacwna.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtuwegvnwa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtdvjlffok.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtarzjxvxz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtzrnpjiyh.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtipiwnbnm.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnqcipkes.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtfvejpvqg.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtgsndfgxd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtbovohtac.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtemaipoco.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtbrdwkcoj.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtgfdzlrdf.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtwtebxihn.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtxkkrovfe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtfwarcfpn.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gthhvcrfpd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtbmxjgcbp.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtenkopzwv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlviwnhqp.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gthkufqbpo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtznqldemm.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtxfarvjdt.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtklnynjck.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtlczawzdd.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtemwtaopa.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgduuouay.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gtzgbpkzlw.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtltyenaip.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtdhilmxzx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthqepjkxw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtldvkzkdi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzcttgqze.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtixtthgoi.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtkebgnvwd.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtvdmsclfc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtbbcfwhip.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtmbxmlptz.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtgkqpedsz.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkpzdvgy.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtulhwpzhp.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtdbtbjwqf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gtqttljxfu.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtvznjejnr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtvubpbjim.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtcuiaggkq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtkcvogpup.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtkddkuole.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gthgqwjars.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtmdaxmmtr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtwbuntxjw.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtstobdaqt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gthodfjikr.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gtvflgcllt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gthhrsdqdr.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtbopgoylb.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtpczwibhu.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtxzyelcxi.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuqyqqje.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtkqfggivk.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtvofoxetj.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gtrfzkzyyf.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtmkjeuswf.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gthssaaynq.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtcvazjnuy.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gthkldhjak.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtjdkaurax.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtblvfwkoj.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtzegntqcd.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtyexxdvsf.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtccufqyvc.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtpbrmskyv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gthvudezct.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gtzbsdwvxo.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtgzoyqsnp.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtkoaqtzap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtwdazgyzd.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtspqaignf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtcavksnsg.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtksdntswc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtsgckogqt.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gtnotcegzn.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtynaycajk.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtmezlwcwk.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gthxxcsecs.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtxrbgpqzl.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtofspbtnd.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdxcxgkc.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtqufaixbh.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gtmwubhhky.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtlrvqrkxo.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtdvocqnfm.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gtaqbeixxy.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gtidyzxgpk.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtlcqadlua.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtgwtlhtmg.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gtsukdzmmn.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtnphinjce.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtbmwuxlpk.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gtilqyasmc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gtvblleolf.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtyfqrdkax.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtaeqodufw.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gtkqhcerfn.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtsiadzrmj.html


<!-- 参考信息 -->