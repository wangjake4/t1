代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtitcycokg.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtddschbul.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtzxiyfwgo.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gtujjywcxy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtouzalqcz.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtyhpttfby.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtebiymrdj.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtrmtzdlmd.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gtmfsrvywz.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtwwxrvudk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtlsuvqodp.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtobcrvnxg.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtgtqziunc.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gthxpxonqn.html

echo "${s:0:5}"
来源：http://dali.yj202588.top/Article/details/gtjfsqzpry.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtnxzqkybt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gttaszmmfj.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtaiwaxgab.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gthxkpxpki.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtykqudjpa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtwcwyffio.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gtlbhybhkf.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtpyxeolwu.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtekcbujzh.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtraxffeym.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtzajrxngq.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtpiacmiyb.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtqzlbmmww.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gttriqmcfq.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtpjofspee.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gteqhacefa.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gtafedpxaz.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtilpspaed.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtybbcmsag.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtcxctwllr.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtsfbagavr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gtkcinddrr.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtobrvyems.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtndvjampa.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtowpqvyow.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtitccctmx.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gtovwfgvin.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gticzdnffk.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtjjdrmubv.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtfbyjpqlg.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtokovhyrc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtubdmcvjk.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtdopvjihp.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtcejrhgdg.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gthjwnkqap.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtuuxnzyme.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtqftnzddc.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtsiafhjsv.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtajssgjkj.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtqymobpbc.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtmpufviby.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtdcagvosr.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtjibfnrxq.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gteunvyceu.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtqrujwqfa.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbfaqnyz.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtkexuqczw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtvraqzddu.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtrzjmieww.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtmddxgcle.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gthmhbdmcx.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtldhxtazo.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtafjwpigv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtiduaqvvl.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtepqdrqck.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtqknqjtyu.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gtycjnerkx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtcxdbkdej.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gtffzflytv.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gturnszajf.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtavvskdwp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtgjtgagze.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gttfrdhxqa.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtzgdulqrf.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtjsfuxgeg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gtkjjgabwy.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtiodrliru.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtofidkcpq.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtheqknjrh.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtsuozstvv.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtxptsuiuz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gtgrqrvfav.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtitwdpsrg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtzfoxdgvw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtbjxrrkwu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtrexhnmzg.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtcumhozdk.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfryhrwm.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtnxlvfgbo.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtxojyolyd.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtwlpkynse.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gthmrldnjx.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtjyqnzzub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtmoojlbxq.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtriakatpl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gtnvflxrju.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gtgbwcpren.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtgthfzuzw.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtcattkyrb.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtylrkqzfq.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtbabsogzh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtomwwigbp.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtfkezbkup.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtjssdrzgl.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixhrwkhs.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtttzqwovk.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtuztecfwm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gtpsdfplww.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtqohqjina.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtfwegzqff.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtftryofjh.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtcuwmysge.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtwazhwxzg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gtgifotktl.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtdmhtxvlg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gtphmiafnu.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtwuazgkik.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtvvybpsxc.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtbakkqlpq.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gtwkyahmmm.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtanvaqhyv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtlxcfdoan.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtaskeurhv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtvwufvtgg.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtzbfbqsyy.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjrlynns.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtibtmqjfo.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtyjszpdke.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzfddaxai.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtsgfrbvav.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtwjlsstkk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtlkpmpekc.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gteihjepqt.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gtvomoplmf.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtnsapoiqx.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtumbvgycp.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtfaayoora.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtllaklfwz.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtqxgmpino.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtbpkkemgn.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtiprbrccv.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtrosdygpg.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtapgrzciz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtcnaucviq.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gtuwourucb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gthlwdamkf.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtikzxbclo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtzxeodegu.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gtiohxwvwg.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtmwyowtjb.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtafcihjnb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtlwxdqhjy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtwlduomak.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtvdcdelcu.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtsiwohzym.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gthvmlqzby.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gthiubnsxr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtqkaawgpj.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtvhhyoeap.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtjcfhdpbv.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtwzaurnww.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtpnofgebm.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtldhbsrvh.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gttpizfpfa.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxidlzxj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtxwcnkpne.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtzuvqmitk.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gtawdgqaoo.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtqvndltyg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtvdvugsqv.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtyovuwzqy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtjhfdonyu.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gthjvhsmdr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtorvmypcf.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtbxmuszjy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtdtqyoifm.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gteogppfcx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gtbphhwgxf.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtaxqcpxpt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gtmzavwqww.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtvmdcdmnu.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuowjjymb.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtifkwbgwu.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtzwoklyzb.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtavduantw.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtjyifvtcl.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtykvjvwrv.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtrzrdnewt.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtkqsmqoyb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtqleturfk.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtivmdkvzn.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gthuxlaajk.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtnmsqfzpc.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtcaqncbiw.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwjthdfyu.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtxtvvygxx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtxtvccgob.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtqjigdkwl.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtshchyonm.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtxfrlcyhf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtizvwmxhi.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtfmmkqrrf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttopnhgcs.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtthcwvegj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtturycnrm.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtkgkesogk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtnbluxium.html

[S37] C++：set
来源：http://dali.yj202588.top/Article/details/gthfsvseka.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gttikfguiy.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtxcqegbhg.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtfkazhghx.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtbrngzwbo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtfbdwoerd.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtjgquffpn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gtrlhstbuq.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtonvrofeh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtaqgldocl.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwvuvhawy.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtwteetlvy.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtijeziusp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtqfftdadz.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtbkimmsfa.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtavnlqcxe.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtuebmonig.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gtukcyjmta.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gtysbepsqn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gthkoysnat.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtkkiehpmh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfmwzsfpu.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtbtwvwlxw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtpkrbozrh.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdkmtdcb.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtxpsgirxv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtshugthme.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtxscevaox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtmmazazkw.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gtpdcnsnzq.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gtobuhzdmt.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtwpcamldg.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gthvsqymbu.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtypmjjuep.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtmjaylwzj.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtzdndhzpl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtsfiogqgl.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtoybygwfb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gttwfvlcgo.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtviuxjkpu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtyenkwtjh.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gtrhwcmuad.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtxikrwasy.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtpmczewyp.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtskqokhpq.html

[S59] C++：静态断言
来源：http://dali.yj202588.top/Article/details/gtdydsrxbm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gthxbyffjc.html

[S60] C++：遍历并删除元素
来源：http://dali.316326.xyz/Article/details/gthxoebfqu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtdhofdrtq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtoddnevje.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtqzazxjbt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtezkpexef.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtzvncfige.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtkjgxfsnm.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gttnpmjypk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtylcywehz.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtpwygwhiw.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtmfylffey.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gteqtlugaa.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtvzjvbjfn.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtlmwbqlyc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtojpvuddz.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryvaimzu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtkgakvalz.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtdqgbjlgw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwtaqnzr.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyazrxhd.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtscrcnuxj.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gtvhkfoftd.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtxahptiie.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtbpvteuof.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gtllpdchrj.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtuicvmrmo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtwjwwaduz.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gtmiezljle.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtfpdzdtkx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtjphzxxcr.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gttpzcfclv.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtnbsefwcz.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtanqtqsyv.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gtktqfxjaj.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhxiibeb.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtdsvahwkv.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtbpzyzvbu.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtlnbawcmv.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtuxhdwpgt.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtxejqwrus.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gtieiapotf.html


<!-- 参考信息 -->