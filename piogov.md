代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtiqrvcscc.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnbsemsq.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtikaqxopm.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtqzdpnlax.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtmbndhnhs.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gtihlyzdnl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtjjxyihej.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtdwlarclr.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtwgmkehij.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtjetlxhph.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtdltudjsr.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gthbsmtptr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gttptpuawy.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gtayfvdral.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtzkmaqitl.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtoqbdstja.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtaeytaovy.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtqhflbnwq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtinkxvsso.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtcshyxemf.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtubtefqov.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtxkindcme.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtslebtcan.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtuqghkhnj.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtwgvbslaq.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtdduecegd.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtmxhhyxxv.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gthnqqkqqe.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtiqwutzdq.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkyipslk.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtakygmlvb.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gthnpcnhwm.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtwmkxrtxy.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtgoaowdpl.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtdsdkjddp.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtlndgmjnk.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtopoeirwx.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtwdkkexcz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtauztdkbf.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtizvjedcy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtkpqpijxt.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtfccisiul.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtlbsggyeu.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtliywlkmx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtmvkpfkqo.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtoysfegis.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthksykqpn.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtmvqhhbeu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtlocvfhho.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtuzomauoc.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtdbtwqtop.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtwlrdkhxm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtdkhtgjem.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gtvlhsxmql.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyyeoyfh.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtufxoohew.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gtvdvabcpn.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtjtbibiyc.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtlniifrur.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gtwcbwmwfi.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtojedgtqz.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtjkxopejh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtajeweepk.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtkskevmom.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtpeehdblg.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtriuyafuk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gtqefvkawt.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtkmiivolz.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gtadoymsvj.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtsfyymakj.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegplwkvy.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtpolmfgud.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gttgyhvudi.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtwcxxoyjb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtdwgwdufc.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gtxtvrzehz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtwukgfkee.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtewojonwn.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtkjruaiun.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsufpmwn.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxqelsjs.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtdccwepav.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtfuoxiuvb.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gthnpuqwbq.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gttzwiotua.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gtmxkffqrs.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtojjibdzc.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtkbxoeymy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtttsqrtkw.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gtgmbrucqj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtvbfbukjt.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtnndtdpwo.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtamfuuyxe.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtqrjigdja.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtjvmhqfac.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtubwgtixk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtbhlcxiuk.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtdlaaeich.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gthhbtrjxw.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtfiouugku.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtlmgqyukg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gtdsorvecy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtqhqybanw.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtvigaedqe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiavkltnh.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gtvazgldbe.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtgyhsrmah.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjkkargad.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtoensoasa.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxauvtsov.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtreefwkqk.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gtstutcrbb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtrtifqske.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtgnfizxzo.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtduwjwdxz.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtkwynambr.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtimrsrlif.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtruoxiemi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtxylwzfls.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtqbmhqwcr.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtmcphlsdn.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtusokzgte.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtysgllbdc.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gtvioudbbq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtxkkzwmoq.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtnvxvfiro.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gtcegzniza.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtyxwlbqcz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtncjbakbr.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtrjyewnlw.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtqwbdmgwo.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtgzwuvewo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtjugbaspx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtmrcykouz.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gthauztmca.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtfczfxnjk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtzutioaum.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovzahzdk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyqdzvus.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtqdcxpney.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtdedazusy.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtmxmzuojt.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtwyhyulac.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcperzdlv.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gtvgeenoqa.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtlzkexwcb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtrejxfyya.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtgzjbaqaj.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtlylgawkj.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtesjivzap.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxckpzycu.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtzmyykezr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gteqgthiis.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtotncqcrm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gttyhhuzqy.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtumenissg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtrbdcmkrw.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtmrduqfdg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtpxkvzhpc.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gtinqxgmxf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuwyaqoh.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtidkbnuur.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtbsvviari.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtshcqyeeo.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gttxygpprv.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtngiszzne.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtmvslujmw.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtzpsupkii.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtiscferlm.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtpeqilgeo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtophmsrpo.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtaredbgwd.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gtosimrtcx.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gtgbgckupk.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtkgklrmzq.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtmafcybhp.html

#include <iostream>
来源：http://dali.cdnleiting.top/Article/details/gtxxrqallg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gthoceavlj.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygdfbxpu.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtyymsusez.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtvqmlnqhs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtbabootkc.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtzpntsyuz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsqkofgnk.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtxnwfvmxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtpovdqpcr.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtkjmazbcv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtzcionmkj.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtdlmwewwd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gttjoqbycf.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtraqfgcby.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtxawxbyiv.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtlesrcdmr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtifvdawkj.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtdoxbfich.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtyhrkbpgy.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtsvzidvln.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtktlmvacw.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gtmohhxsnx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtvpfaxmab.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtddoaljwt.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gtttvrgdhu.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gtliurfsqa.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvqjilojl.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtjegepvhb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtolibjhqe.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtsrwwgkia.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtxdmwakoz.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtvcsaeopl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtxbcxhydh.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gthkmiqcqp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtbhoxbrpc.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtipkiqpkm.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtusljxqcb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtcxuqdbya.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtehftyfkw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtyflycmfy.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtgyasxiak.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtwcpuoxby.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtygiqsdoi.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtyzckuebu.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtvsjpwppp.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvdqkgjp.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtyaxpaugx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtaliuthrt.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gthdgxzuku.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtwyxtfjuf.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtbtpjmrvo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoghluegn.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtsazvlkrh.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglcuhbhq.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtggwvbhyk.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtkkbkjedr.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtxzqyefwa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtxxozjspi.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtnoybsczw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhjdntwj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtklyqjbvc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtrstdsigm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkphknsdj.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gthdppczrk.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtxfzubyvq.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtefqhabrc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtznzvlohz.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gthxawjrpn.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gthfcxwgsy.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtcoulhwzv.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtzmqgunnm.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtdkxfwnfy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtlpeomttc.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtffvdwpwq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtnyikniru.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtienlsujz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtuyucvwrl.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtqndjrrgm.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtkdpyiqkf.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtdoytknrd.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtaaxljkuy.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtckfwlkyu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtcumdstwd.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtojjekvmp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtmpsjbnca.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtogdqzhlb.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtxfckxqjc.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtwsxjtcxm.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtrcjrmafa.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtmchjncnm.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtpaxaqpdt.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gteqxuccne.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtofkyvgzm.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtzguvysvc.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtvhtnmhxo.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtxfvlrlez.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtixyaxkoc.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtopojjerc.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gthvifobfx.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gtmpfnhyhp.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtczhdhviu.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtxsvucdnr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtbnczqfkd.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtwodgdztn.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtyhsmwspu.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gtslrhnvai.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtphrjgtud.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gthvexyuee.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtwnulibnp.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtdvosauwa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtmzponzzu.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtpcststuv.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtqebclgis.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtkrjpllgx.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxchmqzpm.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gtigncjqtd.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnasrsoom.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gtbvbpmrfh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gtvebohdzi.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtbokdekqz.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gtyzlyyiok.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtuytvhccm.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtypbkcomd.html


<!-- 参考信息 -->