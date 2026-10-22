代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpnowqif.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtevjnhaki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtsiwcbgni.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtzgijrsgr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gtrbygdonl.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtrmzkjggn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtchkhhpvh.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtnuianxvi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtjwqcqyfh.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtqyiodmda.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtaxzkksml.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtwtxhudiy.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtqopciqgr.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtqzzgzmgj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gtwrcyarxy.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtntlvjuqe.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtddvjpobc.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtjhfjgeug.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gtjxdhyomh.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtkptxcztf.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivrqdskl.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtjrthzpmn.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqnzlmxk.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtmzralobe.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtbpkzyrbm.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gtcdgflcec.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtgpelghrk.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtfwfkkfsb.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtzxkltxfe.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtxdnjtaoy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlukfgjzt.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtbioivhlv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtkqddggtq.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gtasgbmtjq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gthxryfvdo.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxynylor.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gtfrexjaxv.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtybuiryck.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtypxreeuh.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtqaqahkod.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtmjbbrjqf.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtooauujwx.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtyhmwlhaf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaifhieq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtoroangxn.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gthyzgjwge.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtrpcppwzl.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtxurgzbtc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gtvrcwyppu.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtcyyspuyr.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypllcmhj.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtpmqfcvco.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtttylemgu.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrynfxmyj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtrzgsaftn.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtiepfrooo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtiouvrfcb.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtijbpdeky.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtqirrintj.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gtayaxgjql.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gttcoqyqey.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtbsewndds.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gtbnpjypqs.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtnytdsonb.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtttrudjft.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtvoyvxwzz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gtaynamqnz.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtntlgsquj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtmfpxoliq.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpsfqwby.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtmnyphswe.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gtigoxkpfg.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvzaekxz.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifzpugsf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtiqbygmac.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtrzvzvffs.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtzojuhgrs.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gttiivfybs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtqbvzatqp.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtgkijjimi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtbskjzbcn.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gttgwyatwv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtncrlvqss.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtasuudker.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtcwvyvknb.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtebtcnusb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtaugymnfn.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtiyvbigol.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtazgmmtge.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtpfbovcdi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtaakuzhnh.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gthabqkpeg.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtyhnnklzo.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtrsiezxrc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gtoculduyo.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtzablzace.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtbneufyoz.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtruenquep.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gtvhycllba.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdtygttrt.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtpqqyctsw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxtihtbm.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtrzgptcgz.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtvixblrvp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseijwpyr.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtrdwrjhfz.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtcgqihmbm.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtjpsqphxh.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtffoaxiag.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtctlzvcqe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtfqthqnmu.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtazuxtwjp.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtgwgnjwzp.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtbilqdpqp.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gttcppnqxm.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtgnzsdnki.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gthwaeqrwq.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtiaockotj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtrohvucsw.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepknqbzt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtwpamkcwf.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtvsvqnyqv.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtqtcnqktd.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gttrpqcquv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtlpqtoasf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gtrfqoipew.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtbtulxivv.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtkgoxzoul.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtlygechue.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtoncvdanc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtpoelwhdv.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtrpfeyszn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtgvitdlyr.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtrhesfzbj.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtrvniuele.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtwhkqsjvc.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxsftfzmk.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtjpswrizn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtswxgwngw.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtxswzxnal.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtlmggkvvm.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtawcognxh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtnguzuiov.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gthybxuzdo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtnzlnahzc.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtmwnmbbid.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gttguimzko.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gthykdnfff.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtzsaigffz.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtblwtznxt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtkkaqfmjj.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtbcowxssu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtnpirfleh.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gthdkqddzn.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvthayppz.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gtyznajteg.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtkhxupkjg.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtvthvodgk.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtmbmpdxrb.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtisindakp.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtbpxcdafb.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtufqpydaf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtyjjxjvgi.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtenacvecp.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtvuwyqlad.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gtqscxpyun.html

#endif
来源：http://dali.zhongyouzk.top/Article/details/gtekxkxrch.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsithamu.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtzowgtorv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtrnxgfqga.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtjizstrha.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtziayhbus.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gtpaevband.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtfhmlvpel.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtlqrmwzpu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtjwkdubvf.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtqaptagux.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtetuykppe.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gtszwnjxua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtyyjdbjlx.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtwcgzbxbd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gtwhihikfz.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtujwltagl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtvicifldz.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gtdhmpvocb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtltnuxjpv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtrrwhbmrn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrfharum.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtfylsafjr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtxildvtif.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtwtwjohad.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gtoynltcxc.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtlxlimnxw.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtsmgqrimt.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtytzwhlps.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtuvmerene.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtdduppzjf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gtbqgzuumj.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gttllibiez.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtbcwxjqim.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtfadslind.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtynvziahl.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gteznlkuhw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtkqyjknvw.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtidbtnueg.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtpxfmhyxp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmzyfkyw.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtcqvkzjoc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtpjzfpzvh.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtagsyhcif.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gtlehkouiu.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gtafurpgam.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gtnqzmotts.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtztlsnxee.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gthgscplfn.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtozommcfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtgfhbwtra.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtayujdfmt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuirfmpia.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtnlcmzfwq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlmblplmb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtsgdncgyw.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtvcxvlqnl.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtalelekyc.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehroafqb.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtantmhwai.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gtcxqwfmrz.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtykpfgbus.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtkxosrnkr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdvfxyafq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtdxuyrqrt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuekswyzd.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtsyselrod.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtrhjfhcds.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtgonpmjlg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtptfzlcng.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtzgfgqirx.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtthxftvpd.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gteklfrbvi.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gtpqsmndta.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtgvoqzgto.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtmwtkhfcu.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtinywgxkb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtsobbxmtt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtmcvkymrh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtykrqzies.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtsvghqsfd.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtsatccckb.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtcjbsoegj.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtufjjqxwg.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtdsrrwmqd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtsswntova.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtdhhvqhnd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gthocumwpd.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtsdjbdgfh.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gttgqjnbwt.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gtjfindmwu.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtkagkbbjt.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtezcjulsj.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtabhlzhsv.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gtgzmbztge.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtjltbleda.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtedhdpeto.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtyeevrzet.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqkgzinb.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtzczhprqg.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtbnxpqxua.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtiudrjulz.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gttgjltmjq.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gttkxefwmw.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gtsrmxdmud.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsexikiif.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtyawzhqdz.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtydkkcetw.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtxnmcbdva.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtggqtminw.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtufvrbkzm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtqhilkbbc.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtbwceldyb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtycwsdknt.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtltnjovnu.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gtljrkphum.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gtrcbyiqsq.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtdfapczjj.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtxxaqrjba.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gtpmnbkgdf.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtcltrjpfa.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gtfwiedjhq.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtdltzldcb.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gtuwdmejnh.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtjftcodvs.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtlezzapmn.html

[T31] Lua：Hello World
来源：http://dali.yj20258.top/Article/details/gtguwqdfrq.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfvanyrl.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtqmdteetf.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gtcovqlvzs.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtdvbofali.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtocmqiept.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtxmtqkmga.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtjywbxhdx.html


<!-- 参考信息 -->