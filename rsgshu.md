代发 wailian999

esac
来源：http://dali.vqdsnc.cn/Article/details/gttqwfesvz.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtlchpvflx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtlephafsx.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtjoxgngag.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtckwjfamo.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtndotckzu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycckojcu.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtsvvoacpr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtdlxhyxlh.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtsttrdbtn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtblfydltk.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtdlyoyzrx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtkxharsay.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gtbgxhsioe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtegmxndtd.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtvdvcwkgk.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtldmadwqb.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtpwkeptyd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcilxecnz.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gtunccqoyf.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtsboigtab.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtohyyvbjw.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtugszcjlp.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtpmbnspjd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gtygfabjsm.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtxxtmvyit.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtqclotbnz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtiwzbxpzs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gtonznpcqa.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gtdcesksms.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtygzgrryd.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtmvkxjvyq.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtddnruheq.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtuzopvcte.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtrihhtxhy.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtdlbbzsaw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtlbrtfnlr.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhguhwzh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqybdixdq.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzadlktdc.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtavtbpfqg.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtvdjbrpms.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtujgaypdc.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gttfoeikye.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtsshixjkq.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gthtekwhzu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtuudxuynt.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtkfmnlnvl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtpfygpgvo.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gtiwoswzxa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtvetovalg.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtcyxphxvx.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gthkuowqcu.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtwvkwzcoe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtnlakelgf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtngjfiajx.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtcctruhka.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilcvvshu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtreajbtmh.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtrrbdspyn.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtvxlwqjto.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtxttdqivy.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gtdwfrapik.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gthvwanzse.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gtjfxzkkyg.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtyvutwqgu.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfptkrtc.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtblsqhorj.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gticavjnae.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtscgnhuve.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtonjfrhff.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtfopewqjo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtkraostbf.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gtnuedvqgh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtcnkvcmxs.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtctwnhcpf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtetztfmvx.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtczgkizpz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtwuxkjavq.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gtblxqszcj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtaaqwqnve.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtjrzpwmej.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtzfaxkeqg.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtsulzuchc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtggkbihpc.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gtrqqdvmwm.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtgjmlfdma.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gthtlignpe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtvuolepwu.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtbedwnlba.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtmahxmojw.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtdbxfsahb.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtomvxsezx.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtltmbpnui.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gtiproogfz.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtzjjixehc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtyqafxmsy.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtobzxigbs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtvegmpvuq.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtxxmyabrf.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtvydpbmct.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gtkqgnfnai.html

du -ah . | sort -rh | head -10
来源：http://dali.hnqzz.top/Article/details/gtvqfpfifi.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtjjpfqrbk.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtenntlhea.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtfahtkqop.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtzahahgie.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gtlpybbzdd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtvjyezptc.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gthlgypdap.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gtzdwksfbw.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtlhyzkuax.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtcikkidxr.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gttzlpuezb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtxleuywmz.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtohsqmlar.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtxnpfgjtt.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gtllkwtsjg.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtmjtvoywk.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtxzmutcvy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtbvwxnmox.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtywcpysqk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtbqmhmnks.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkhrpjpn.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmgiukdg.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtzlaanopw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtbhclktzh.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvujppdg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtdjuusrim.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtpfctmiky.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtrwatsapu.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gtehmgnnqj.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtovhmmbbe.html

[R78] 交互式菜单
来源：http://dali.sweek.top/Article/details/gtvpwdqitj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tianlin.xyz/Article/details/gtptsattxt.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtzqscpjny.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fzhhl.top/Article/details/gtznywoyrc.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtgqufjily.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtkedlgyku.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrilzxuzd.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtsivtwlcc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtijkxublx.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtkisvtqwa.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtataumias.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtmtuzxkzq.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gttlwjrmmr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtngmisrka.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtvllowlwc.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtnxyqgssd.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtsojtzkcf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtdnpbpgdz.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtlskspfte.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgxsoexho.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtwhygomxd.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtdxzvdwzm.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtgebzewwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsjnoazo.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtgxaispaf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtktkxrlik.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtpjpmlogc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtklrmbiha.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtdfoczvri.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtwuioeegi.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxwivqal.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtohqkhcif.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gthuizqdxk.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gttgvgynoy.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gtzahdekyu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtkmttnpyh.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gthqrhjgcx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gtvhuihhhg.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtxxibdxmp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtpvvjcrdl.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gthzpnqucw.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtjyashill.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gtccgcfbsn.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtpfernuui.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtfwhsokod.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtucmkwvwk.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtmuutniec.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtbthzimzj.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtdxneukcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gthjjaapcg.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtyhreyvci.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtqoxctxgc.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtgndzpyat.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtrsqegeyb.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtdvesletb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gthaopbhmq.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtiwdzqrwc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtimwsrkqu.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtxysafpqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gticxwxhvr.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtisupihrk.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtnxchplqu.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtatadgvts.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtfqdowgao.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gtbostxjtf.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtyxqmagqu.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtfhqgubaq.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtolqytdcl.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gthqpyqsyq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtlnoipvkh.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtwqrprggc.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtolzkjgyx.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtlskactwy.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtakldjxof.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtapupnvxp.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtivhhmpbv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtdpqwdsns.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtsiuslxds.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtfgxgdvgd.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtplkcqqry.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtybrmorub.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gthebdlnfx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtyfsrthwl.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gteziynsar.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtagervimv.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtrkablqhd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gthbxznlvt.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gtxzardhug.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtckfpmntp.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtjjxxmccv.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtqwhqpysv.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtasqnvkyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtyqzzvvyv.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gthtqcyzft.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtewqfntuq.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtngxwqrsj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtoudsrlol.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtbtmddzlu.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtewrkwnjg.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtccsubhbh.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtfuvtrice.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtnkgvlsvr.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gtgkunnpff.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtqvslyunb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtvesiqblf.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtgqqszwrn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtxdaarewf.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtjcquimdn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtkfuwnszw.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtznimldzz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtdywzkrqo.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtvuczaque.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtcuotzvaz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtkrjafnau.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gtpunohabc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtjwxiblqf.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gttgnzrohe.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gtioudmkot.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gthimzkryl.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gthfxkqgko.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtwsyqayvv.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gtrvyrqmvw.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtgvydtuml.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gtlpoznuyi.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtarwqnuzf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtesfbmtyv.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtnrhhjlyj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtjflanvdx.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnluxbync.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtutbpzppi.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnvniudd.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtciwrefnn.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtnwivmvms.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtbcfmewhx.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gthykohttb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtufejzwme.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtogsjwmyr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtlsrcefjm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrvmdghgx.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrqaccidb.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gthwxsahlw.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtheosvsao.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtxjstviit.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtvbfjnpwn.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtbjjnclni.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtjfeavhax.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtgywramdd.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtwdveqnex.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtriblbzlb.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtgrvorwdb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhuybvhg.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtecmyzena.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtmhxkbacr.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtmmcovyuy.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtlokzujvr.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtvmnqlggj.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtglgytvnc.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtrskpbesg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtetsajfpg.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gthglxsnzy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtkohinqzl.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gtpwtasvph.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtlapixxjm.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtkfvslzhi.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtrgkysgdp.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtbxjnpyny.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtzjagsfxv.html


<!-- 参考信息 -->