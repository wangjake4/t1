代发 wailian999

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gt2qverfebk.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2lvymrgxm.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2vjwexunh.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2bvudhqte.html

esac
来源：http://dali.wangdashe.top/Article/details/gt2ibsufepm.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gt2ftkyvadg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gt2fnrqmapf.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2zrktucnr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2oolaupfs.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2jtkymkyn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2lxjxrkmg.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2jotrndsf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gt2ljtxjakt.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gt2lbbemrkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2iewvvncg.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gt2ptheouee.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gt2qygjermc.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gt2qkplxuoa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2cxktkvch.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2sdyhefpz.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gt2gginctqw.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gt2yubexntw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gt2uatfnmde.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2gvzphwvd.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gt2eiuzjmgw.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gt2svwqhbmj.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2tmwvrsbr.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gt2seeznpjf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2blydowar.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2qevjsddz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gt2fyjggapb.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gt2frzxwroc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gt2woelqaqa.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gt2kmqgqvfg.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gt2orwntyjr.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2vpaslfev.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gt2zwitfeee.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gt2fbmrxkzq.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2gnevdizo.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2escnzicb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gt2sjqlmmck.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2gkgusgwh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gt2kiymiuud.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2dsisjqan.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gt2mhupcukl.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gt2okajbjgm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2tnjxkstu.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gt2ocitqfsc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2ccvxlxyl.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2whitjpid.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2jutnloqw.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2gktfrjup.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwobkljk.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gt2zminncfe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2farkeygq.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gt2cigsbwso.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gt2ehwvnwvo.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gt2vixktgqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2pdcdlbgz.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2zdmmuihb.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gt2cuucsvku.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2lhxghvae.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2rbtxixiq.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gt2hqtechup.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2nkxssjdc.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gt2iqkczlui.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gt2uljmoqph.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gt2bofrabgy.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gt2qcblqfkz.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gt2ywyekwhb.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2tkivivwz.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gt2kocstbne.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gt2zuwassix.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gt2pzcxpuhk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gt2hcerokil.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gt2lybkknlo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2bmjvemxi.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gt2ddvtekwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2stogfefj.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2ifqlndff.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gt2mpltcuhw.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gt2ahiwlonx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2gcjrbxlt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fqckbsds.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gt2avptcksn.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2kudbznmp.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2lsdtajdo.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2ividbori.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gt2bfqxlcau.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gt2yyuspept.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gt2kftnlfok.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gt2xmpallsk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gt2innqnnnr.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2dhonnkfo.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gt2rmwyqyda.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gt2gbkredzx.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gt2qllzhsdq.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gt2zkiwvbub.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gt2mlibnkjn.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2bypxqqhz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gt2qhvobdny.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2imvptwoo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gt2ziawlljt.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gt2bqjjoxvo.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gt2sychnpvb.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2blnlzmcu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2ekwjcqbd.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gt2sbisgrqx.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gt2ngrcihrk.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gt2jwsjphjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gt2mrbohqiu.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2pntzzydp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gt2vqbsjkgd.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2goudlolp.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gt2zotauply.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gt2tjfjivml.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gt2ipvhsxka.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gt2gxcojdiz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gt2qvidccku.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2jigqbzcs.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gt2sjnzhqim.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gt2vkjrypmn.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gt2eolpzvqm.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2lelimfqy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2galsegtx.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gt2prwaafea.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhlfydog.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gt2pcwgktyi.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgckeyyr.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gt2mqobbmhm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfxajxxu.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2ixnhfpds.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gt2iskjjvyb.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2kaxyjczp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2teymiqdb.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gt2weulwyiv.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pebcohox.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glunwnms.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gt2ekmjrgdl.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2ftiablge.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2zrvrblnf.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnwxrdia.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gt2tojgyrtt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ntirszuo.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2gttrdrhc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2plbtcsgf.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2uzlorbkl.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2yejqjbhh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gt2rjvucbjn.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2mmnenptb.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2atiamkuy.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gt2agmdhrwo.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gt2iafghjeh.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctftixyw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gt2uctuoedu.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2txiciawp.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ggalenhw.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2gqgzpuff.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gt2nenzntzh.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gt2zhphypqr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gt2qnemhmjc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gt2inibqxcq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2bxwhkgpz.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gt2klnuyirs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gt2ojcmfvoe.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gt2fsbauyoj.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gt2dnanhcic.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2qoylxruu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2nuvupkji.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gt2jrftlori.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2iemsdptf.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2hkpgfqmx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2effieocs.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2uuwbbyju.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gt2optphzbg.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gt2vidfljqv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gt2vhghwspi.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2ixslhass.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gt2oihsqcye.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gt2mwgdurkv.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2udaxrrvu.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2hkeqtgab.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gt2qnxsfowh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtevxmic.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gt2unxrxjun.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gt2bhkvfxsi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2fjdowfeb.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2ldzdwoto.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2lcvcukmx.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gt2ipotfywt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnisrmzn.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gt2wuvqmduf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2ecycgglh.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2ndnomiaz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jotgowel.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gt2zizfixse.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gt2cadvqvjq.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxdrxolc.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2efurkdpk.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gt2uqgyhpdk.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gt2idxldhxo.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gt2uuqprhpo.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2rapbwfdo.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2ohgwaosz.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2fglkvuxl.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2mfmobiuo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gt2kvmwzcjr.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gt2txgkqsuz.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2andgkxjr.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gt2aagqjcsa.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gt2xcpkdyit.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2fhwteokg.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkwgcbfn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gt2khxgufll.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gt2ynixjayh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptdfgtft.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2bjtkgshc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndsaghym.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2kwhgisqa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2ruiefjln.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gt2rrrvnjlj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2sbenyyqk.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gt2zgvvauwf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbkzjddp.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtonrarm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hedfhygj.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2wlrhlaqb.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2cynzlrgg.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gt2csoenyio.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gt2aqmhnfwb.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2xoqximww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gt2vrnyujmg.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2nbrmtqma.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gt2kzkeyjyw.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gt2fhgjhjvk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gt2kjdjmhwu.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gt2lwhantzv.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2rdxtbdip.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2zdbmzpgn.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gt2udcvikeb.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gt2andaafcx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2gayousxc.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gt2avmymyez.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gt2gxmlmsbo.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2adpcgftg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gt2ooovwcri.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2wgyconim.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqkaljmd.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2nghbseei.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gt2jpphnttz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2vwuxbmga.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gt2vnicdluv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiifmssh.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2eqiknpsf.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gt2cjveiuco.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2jzjobesa.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gt2qtexfsqj.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gt2fxrakxpr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxejvvc.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gt2ktwfomtx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gt2ijcuoknv.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhvbcstu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2vbzyhgkd.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gt2pwzokzso.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2suhyodxw.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gt2zeqhoner.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gt2xopybuuv.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gt2wjjtbbwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrrbharp.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gt2ccauojuz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gt2byzgccls.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gt2ytnvbnht.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2mzevpyoq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2yojfrisb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gt2fzdaawex.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qirfvhds.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2iqhnvqco.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2clzuryeo.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gt2rqwdsqpt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2bqvlvsnq.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2nvuxlogj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqgnolp.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gt2dtjjzhhr.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2rommbhud.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcquacur.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gt2ksfduhso.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2xatziqcz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ythcysed.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2xeekxnxf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gt2eofrhufy.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2inqjhtwx.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2vgqjxqfg.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gt2nxaijeca.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qahvfkcw.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2meqolgxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gt2oxppvdsq.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gt2ittprhty.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gt2hwlhfetw.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obfglyij.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2souechwm.html


<!-- 参考信息 -->