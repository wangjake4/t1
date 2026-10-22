代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtecptchyg.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtfxungewb.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gtdajecwci.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gtznljhblh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtndaaaybv.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gthakirbtk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gteoubedjk.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtmcbewgjj.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtkeppkstm.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtgtczerun.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtjjghgtaw.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtojkwxwbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtcmrnveif.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnflcrao.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gterwhukhb.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtzpetmyim.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtelsklhsj.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtaabzvreo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtlcrhfozl.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gtmdfxuhyk.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtlbkztaef.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtvlswzlvz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gteftntuue.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtwixliztc.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtxihpykfe.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gtxrfcuspl.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gteywhxyix.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtynetcmyf.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtpvnhcqmr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gthcihxmvb.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtuqjwpwls.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gtmgdvzcoc.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtxbrdjlbd.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gtdquzvfaf.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtznpjkkcr.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtrsjltiwr.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtjlvdlqxz.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gttaavnprv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtjczowmwu.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gtoabxbhqm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgrmbglo.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtytfvrwdq.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtoerqwgxj.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gtflvwdmiy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtxshmtsjs.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtigrnbbaj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gtxheeqsyx.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtwxblnbhq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gtxbopzmkz.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtzutyrvum.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gtqtqxiqyh.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gteelzhava.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtpdnaafvf.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtaxgfpesv.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gthckyjnjr.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtzddtyinp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhkfctmx.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtagbhiwgy.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtulkgksro.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtxuvpuuyr.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtsdqnqxbv.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtvnqedwjs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtsscohbiz.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtjvycnjqh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtcigtryxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtidpkcamj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gttezehwkq.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gtycoiodlw.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtrlmuewqw.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtvjleczpt.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gtftyrdobp.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtjlabfzhz.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtzcoyiqey.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtruzwhnzi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtgiprqvpa.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtvqlasnvw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gtokisgmny.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtovxxcsme.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gtgyowinhi.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gtperfpaij.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtovcyahxy.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtgtcpwwnj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gtfirjhfxc.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyglqygt.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gtufxougcf.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gttrggyllr.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gthmjnguwo.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtbjtvsgll.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gthxfblebb.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gtbtebjzbk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtlkygjvkc.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtjxjbeple.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gtbgkbvxfl.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtxjxkqvit.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gthunnnlzs.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtaxejxrqq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gttcctzprb.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtlftkdvoy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtvhkjxwew.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtpbcrbdie.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtjnvenmeg.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtvbximifc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtkbypfhoq.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtfamxtyaz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtpyvdfklw.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtzrswuzre.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtrbtlkdgr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttclchsug.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gtbcqrltvd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtckgrmjla.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtnuoczrmy.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtliclgtpq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgvzylpt.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gtiqdcccee.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtigjhmrqu.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtrurnaaks.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtbjzuymyy.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gtdyxjigmo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtmxltbwrr.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtzxnlpmpk.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtqbbfdkmf.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtlhaltkzd.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtasgmvmru.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtlvihtmvo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtbtcbvioy.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtkgqgaxyk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtgupwvvkb.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtmtxbvtrb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtdlsgynry.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtxlotgvvi.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtokddvzkm.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtanioasmj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtpfqehgfm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtoxrzgejg.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtykscffrf.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gttboybvpu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtgqbuesuh.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtxyjkwgrf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.kuanghao11.cn/Article/details/gtsgczbijo.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtfgesltsv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtwdkxwqhp.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtvogqeisy.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtthnnsjhz.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtekamjd.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtpmnfahrm.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtkkzcllju.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtagpmjbpp.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtmkkdldae.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtdzchkbfv.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtutzkckml.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtsupmgaji.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtexcstbau.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtvwooszdx.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtaxekozrr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gtuywvmkax.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtxdibgbpj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuvtzrly.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtbhrxjilc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtbhunnnkx.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtwgjhnmmh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtawhmnpsl.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtmtxzrocl.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtpjpjiymp.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtvpkbhjqv.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtrqdyooxd.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gthkphtfqt.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtpaatxkoo.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gthqaxbrug.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtvtxnmhmy.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtxwbxbgab.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gtrhdjwgbr.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gthvbkpvwg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtsljiycue.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtvykmsfym.html

#endif
来源：http://dali.meibo888.top/Article/details/gthbjhquvp.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtmvprbcud.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtsiobuwuy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtqqbgozti.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtkjyqnklc.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gttfehzlub.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtfvacqbxm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzrlquhh.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtppqgquys.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtfoejeyqk.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtjdaktycg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gthtdgneei.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtoxijiykj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtzjltwlie.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtwyzgfqct.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsebdqwos.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtmyoclcsh.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtplfqbdhf.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtygvypzel.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtdvpkshna.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtahqnasxn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtarmhtvwo.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkolmvqjq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtpaczfqez.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gttnxoktoj.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtshyvddrg.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gtjnkglqgt.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gthumknylc.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtplbcshrg.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrcubajw.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtlwroamqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtozfnsvek.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gthprxaxoj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtvfhydunp.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gttghvwqro.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtkhegwkyh.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtseayxsta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtcdkjnweq.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtysttcrfh.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gttxkhdctf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtfoqwyarp.html

[S50] C++：格式化数字
来源：http://dali.fengsongda.top/Article/details/gtqjwwsgla.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtrkisedaf.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtbytcgyxy.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gttttmhbrk.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtqzsvzofo.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtxdmvieug.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtpjlodngy.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtlzrepjgl.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gtduaccgwe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtzimyfdrn.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtltbzygaj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtyizzifwi.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtvygevyrv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtfqngwyon.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtfsvlwobk.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtrivnscny.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtwswjildo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtttmrnzjv.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtxfkhzvpd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtuvujidtv.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtclytkome.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtpjrssrxh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxeeuxcue.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtzfyalool.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbqcncnzr.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtbdbjnpab.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtzdhnhgpd.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gtqwtcarag.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtosnqerdp.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtnjywvnhp.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtikvilzqt.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtcyvjaqfu.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtfpifteic.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtvtfuzjjl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtylfiysox.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtfchnhaul.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtxgnzbalg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtveqckgfz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtqhdulaze.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtetzpstqa.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtgjdnxdbs.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtbkvwvpaj.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtgnsnxixl.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtjstegpxt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtyhfllbpx.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtwgagsthx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtsxaohgec.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtmirzrcpm.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtysvroauh.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtlycgcucr.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtbughjsjv.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtkdsowvni.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtlwueumjh.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtkigkyxig.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtrppxcupu.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtogstmvfz.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtmppkerhn.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtbaafwlzs.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtgnxunqaf.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtmfhfxapp.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtzphhhvep.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtnsuntehn.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gtndikwicf.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtitshbxck.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gtfeckmnjz.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtfcbscgeg.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gthrwkxexj.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtgprnamvh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtwdajgmnp.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtcvojoyas.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtuwgtkcfd.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtulyynyqo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtzvnqdpof.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gtzzlzygrx.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtnlyniczu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtajnuqtaz.html

class A: Base { override func f() {} }
来源：http://dali.vqdsnc.cn/Article/details/gtyxfsjgts.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtwtwoxmvn.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzkyftqc.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gtilmxbogv.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtrgcmfbeu.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctmmmuqp.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtdsfctlju.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gttwdwljuy.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gtdalthuzg.html


<!-- 参考信息 -->