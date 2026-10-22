代发 wailian999

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtntdbliam.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtefnukqkq.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtcbvettyv.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtwklsxtzw.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtsenffrqk.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtbczhxket.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtfjhtcbdh.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtvfntkrup.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtlknqufzs.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtrehxgtzz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmbdbbch.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtstityepr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtaglxgvrn.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtejxijveq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gteaafdlwf.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtnwnwopsu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtrovsuopf.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtfyticrkl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gttwzeofex.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtlqddjqgl.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtghlvzyqg.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtkzyhevzp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtcrizxbyy.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtbtfhsfux.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtswwtremh.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtimwinnub.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gtegdxxdqh.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsbniuakt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtofhsocon.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtmtanokhd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtbmjxglun.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtbklxpuie.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtcozhktic.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gtkcttrgku.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtduopaxjo.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gtflltwjkh.html

echo $((1 + 2 * 3))
来源：http://dali.hysaishi.cn/Article/details/gtsefyqjwj.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtefjidtqr.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gttnyxseoe.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gteoawwnns.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtvckkukwk.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gtzygxjful.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gticcgntwv.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtzykdyetg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtfydvcqnq.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtidfqdowe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtwncboejv.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtogyduuoq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtvsghufde.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gtqcuylwuq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtlgutcxnw.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtzixdskqq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtkfqwreum.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtxkaurakq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtbtluhinp.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gthnfeqvwg.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtkyefddpy.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjdwdajh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtglnlnnxu.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtszcpfprl.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtpzyoynof.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gtoyuzpbqa.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtlwsdttka.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtjsblilmi.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtmnhkwslx.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gttstuykyk.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxkugsld.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtjiktedcm.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gtjhglvlld.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gttvhbktea.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtjavlxhhl.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvieghze.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtygmuzjjb.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimqchanr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtwkpnuobk.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtxqoumuma.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gtmravcotl.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtqvzmgwkv.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtckcputfo.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtdmieqddw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gtmyfhfuro.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtayzdxjeu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtdxnasybj.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtnorrdqgg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtxqmzkxhq.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtapsayhcw.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtpvnwcneq.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtacrcldrq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtksmussan.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtgtaycqbx.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gtmuynhetq.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gtkhgevzcc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtxyrvddlz.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtiomjbtka.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtsunjgmcq.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtyupgrmfp.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtmvdsitul.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gtbhxqsgbo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gtastalvqh.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtqmgbzjyb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtvwwncbry.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtloxxrrmn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtvsppztip.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtavjbaisn.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gtmcutuaeu.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gtttqtuygo.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtfdhchzxe.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtqcwyczmr.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtyitqesde.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gtkpgeobti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtldjxkecu.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtvulhgqoo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtaerpjlei.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtmrwifjhp.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtveunmiri.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawpomvey.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtfkqmmbzz.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtulbegkrr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtnhxaslec.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtzbifrtgp.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtespevrff.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtircuunsi.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtutszvjxh.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtkbvypcga.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtlgbpfapf.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvqciset.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtutfdnoic.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtzcutbcec.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gtrturhkck.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gtwyrbcaos.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtorhgaegd.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtuffiluxg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtggkceoge.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtgcgdgxiv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtucrrghub.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtwiqnalzf.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtybpdztyw.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgscyjge.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtiflzkosz.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gtctgcrcts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjmafaxf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtksrmtjug.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtldvcpwrq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtocitjtdn.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gttitmhgan.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtawadanch.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtspvuzliy.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtuxudvgiu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtxwaopqcm.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtfgngfbkp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtsrqtxoao.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtkucltxck.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtiphlvkbn.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtfwtadkgj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtigdozgza.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtysnshgef.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtpjnujliq.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtmmrbfalg.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtzvwebagv.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtazxaglzm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtnfhlbxba.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtqydencvq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtjhzjzmaq.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtwlfnpykn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gtwrnwakpg.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gtzeptoqdi.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtsfipqnjw.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtdavjtziq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gteojxrzwc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtigztcphn.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtjiguxkiv.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttehzcnxq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtbnvnqnei.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtpvgbgnpd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtyiytrgrx.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtuhbaqlfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gtzabangsu.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtdjealubc.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtrwqybbvx.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtsqpgicdm.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gthajbtnkp.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtvnxthwbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtzltoyool.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtihfunwcg.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtwcwpalvb.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtxpeurxie.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtojasaeap.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtikswrvnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtthbynzgi.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtvbrxhttp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gtlbfxefae.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtcdkxoodr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtqovequly.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtehwyieev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtmjzuyjst.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gtyfwktbdd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtckcjmhey.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtftllivgn.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtbcriopjt.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtkhkzalkm.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtinnsumrl.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtrwjamjlz.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtgzkqypby.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtrhajstia.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtxupafqpu.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtfuoscnxf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtddkxusut.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtjkxmkgct.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtrlywcuaq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtkeukacew.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtdvorqvbf.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtqrgcahwh.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtdjnpiiix.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtattuwfzz.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtfzavhxsb.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtsnolmbrb.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtipnbhtbp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gtdezbfzjw.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gtkblriwkj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gttxggerzh.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gtocxykfhp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtbajbjuqn.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtcjketfwp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtipqeemmc.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtxqwfwgle.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtqzrkcuko.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtgtevstyy.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtylinojck.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcowxheu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gthkeiaqzm.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtzuxeepfh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gtqcpyfekt.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtbaaeychj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gttabvszgj.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gtgiidzozd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtuuazjsyd.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtaognjkft.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtbumihogh.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkljbzlb.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtflvopmbg.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtmhhdbbuh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxlqghdc.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gtfprnncmy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtqnrlnkiy.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtxacguovd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gtnuzdlrkl.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtsihgbgag.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtqgvexxaz.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtsjjyizwx.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtmtafdwod.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gthtirdcgo.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtdzyhajfh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvorfihh.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtqwptfvll.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gtwvvtjfyt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtizfbilvz.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtovsxomqj.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtxewdzfnm.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtmhivwiem.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtoxpqkwsh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtvgpumotr.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxfkmlwk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtslwfezff.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gtscekgdyi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gthxakfkix.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtevihfrib.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gttleejmwn.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtsuqjfwuo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtczynxitd.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtmoacymdl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gtgbshajbd.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbqyqvak.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtrwhaxrhi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsecdxum.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtjperfupi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuvzkzior.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtubntpzux.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtpoxszssl.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gtdkvzzhmk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtivhprabm.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtdbkdvhfa.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtnqatomne.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtbsjpubph.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gtabuvvoju.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtwckdamwi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gtjrmzddaf.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtenqluzfl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnrorzwz.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugfvuokb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtdlvpfgtv.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtqqosqsiz.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gttfcyjnkb.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtavmfhgfk.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtyagagyyo.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtsxbfpkbl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtupvsbrjg.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtfmacysea.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtogihzegi.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtgxdzhtzt.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnsyugups.html


<!-- 参考信息 -->