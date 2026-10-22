代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtfhurjvfl.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gthpdruldq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtdqgongjs.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gtujiccjec.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtifsvtmby.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtkuxfjwsr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtriflxpcx.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtjflxuuhc.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgqzxugc.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtdrsyfuzf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtyhfzkuxv.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtsepbykct.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtwzcyhjln.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gtiewocwbg.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdctfmzww.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gtelbaszbi.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtifplksos.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gthqcpluhb.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtpdaiwsnz.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gthxfepevq.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtdmmmlzka.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtspplemko.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gttqtbyaap.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtsbhiwuxq.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gttcwtusgg.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtqqtwasvd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtcmasbnrv.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtxatabrxg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtxvroweur.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtobkcygsq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtuyoauyfc.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtavionhfj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtpnhurgfk.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfnyahmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtiqvurwts.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtfcrqjsdp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtljupnopl.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtvztjnqfy.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gtuhabyfvb.html

[R53] 查看文件头与实时尾
来源：http://dali.guannengcc.top/Article/details/gtcatjrpte.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtlhmaztza.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtviavtuln.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtjeognltd.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtvxnvlyfr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gthwlpybpp.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtiymsftsz.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gtddlehncw.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtzlmmifgk.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtxriskjuc.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gttyrmwsni.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gthsqpqwhf.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijklfwsn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtvgydhrba.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtyclettsm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gtuirmavzi.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtzxmvtggp.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtiiephuwv.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtphdwpsjx.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gthposjykq.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtfkhdbcwl.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtxohrqujn.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtcqeqopqc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtmcyporbd.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsnvyczz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtrsjvhvxb.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtftkkovsb.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvlzbuwy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gttgitenms.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtsavmcbqm.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtqrnzfeyj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gtbltavxqv.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gtuxhezyvd.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gttodovnxp.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvjpncva.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtgkpdkwsl.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtwxbtlrvf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtgdnfvtfb.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gtszzbjmea.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtajmbwzeb.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gtuohtpkvs.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtmcyarlpc.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtetliqffq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtcjcultsz.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtkrorghwj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqipdwfiv.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtjiuebnxt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtvfrbnygt.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtrmtrdgzz.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtqnrgyphb.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtqnrhawpx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtbvpakwli.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtiyjhzgte.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gtprdyfcgv.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gttbpbxjxt.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtnzchwcql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtuntrpqlh.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtyncygywt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgguuysxo.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gthahcqgne.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtgbyusnyr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.kuanghao11.cn/Article/details/gtkrazmxju.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtyhtuljlb.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtcyqspbud.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gtjdkxxuut.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtabksilxe.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtfqqkhbsz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgzvfhbv.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gtmwfvxqbh.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtseuhwidg.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaudkowg.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtopnglxxo.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtwmbhbijx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gtvghkwixs.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtcrqecsox.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gtpuqfdxrn.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gthaaccgkv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuewrgnvc.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtbbdaeooc.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gtzszixuco.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmqtbmwav.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtnkyqyojr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gtdmzfhlzt.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtkmtzbodv.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtmmzjiksi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtcqphmvsi.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtdufvcync.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtybskwoqg.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtwoiwzvvs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtshesurux.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtgtlxqvqm.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gtydduuwwc.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtqinayvmi.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtqrinhwre.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtyxafvmcg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtgaaoooci.html

[S18] C：命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtdnowwuch.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtlydkljqk.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtfutfhidt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gthrfmmqvw.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtbrxbvgfw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtfpszorow.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gtddrbytsn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtzbcxjbrw.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtsudtmzqx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gtuyioshdw.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtsvglraea.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtwcitvyii.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtuonpuqnw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtaqtcbtwo.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtbrefeceq.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtmdlqwroc.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtykfgyuax.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gteprgpqoq.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnvskfwi.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtxgvtpmdr.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtupobbcbl.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtupkjncan.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtqgjqwzoe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyzbjawn.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtwsyzsdja.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtnwwkszvo.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtuxcunwjw.html

#endif
来源：http://dali.zhongyouzk.top/Article/details/gtevonskak.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gtsbkrbfka.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtyufvycea.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gttnppdghq.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gtshzsgfxl.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtrwzerntj.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtioubsiuo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtyznxhcya.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtdfxgbwaa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtmtdkatzf.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtfeqjhiup.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtxqlopxzi.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gtfwgfckai.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtfeuzjunp.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjebrhmvc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtmdywycrx.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gteemgatvy.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtevffgerz.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtfsudtjua.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtsetfkwny.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtidqdivup.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtdmrhufui.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gtskrayhgi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtgqqzvcdl.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtogwxchup.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtuaxqwogq.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhoszfug.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gteyvbtuuf.html

[S44] C++：引用传参
来源：http://dali.9152youxi.cn/Article/details/gttptichvd.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtfhjrrxur.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtovilomyg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtsxndfkrz.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gteobgtfkk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqixpmra.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtlldforja.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtyuekydbg.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtktatgczh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtpbavemfw.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtmazvbljc.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtlbqrjosv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gttxtjfkxx.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtgzolzkoc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtpyddqxio.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtgwxhytqm.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtusogjtzr.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtdtloaizu.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtkwauggdf.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gthrnriktv.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtcpdzmdzm.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxzuyywr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtcvqovsqz.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtyyhirulp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtlrsuzkfz.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtkrgyqtzu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtfivbezop.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gttreuqvjd.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtmjbjbwhl.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtfxuihzvv.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtzkfyknau.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtvlayeksx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvlzqypa.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtrhfuamjv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtwkbzbpwc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtabzctdcw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtrhjvjnxd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttsluxbtf.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtfdnicvfc.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtklmxtxnl.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvaesdep.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gtwturqlem.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gtxtvmhocj.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtlhzbfmof.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtywjezaji.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gticeuyomo.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gthankpefq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gttqosamii.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtpwwlnryh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtkreczcuc.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtynrftcyl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gthbyhjqjy.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtwecbvuxb.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gthsxohlgz.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gtcysmpvua.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtkpunmsqc.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtogpqghaf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gttvyustam.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtpwwysinx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtitmwptob.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtqxrmedao.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtcbafrfyb.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gtwqkumyts.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtzcfdyqyz.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtvabwnsyj.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtvfxehdac.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gttkrjzayc.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gtjisbubtc.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gtmlnqajdj.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtxbkveoar.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtebspinko.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtxqhaykzn.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtdfqzvkqp.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtijhycejz.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtbgtzxpnh.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gtddvhclkb.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtvccvixxv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtfnzoebfv.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtybdmnlyw.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtbojaxafn.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtrhcymxen.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtzfkifhjj.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtqhmcrcwl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtuamdxmoq.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gtunrftjis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gthwqmryvm.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtcmngcbps.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtlazuhxba.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtqnjahdol.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtoytrkdmn.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gtsobgkpjr.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtllzbikqp.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtyrlsdmuh.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gtmytygids.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtouhayhdw.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gtejaxjbpx.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtvamnbwgf.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gtikjevhvw.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtpfpgrxei.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtgimeghtk.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gtxleugmuf.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gthbqygdfo.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtxabxqfbm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtkfoqizwa.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtckyipumn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtlazuvcdq.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhzcuvyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtvzklhukf.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtesoixqlp.html

function add(a, b) return a + b end
来源：http://dali.mhx1999.top/Article/details/gtbjzbgpma.html


<!-- 参考信息 -->