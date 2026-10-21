代发 wailian999

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gtpnrwuzaa.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtogtogevl.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtdgrbnpmg.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtkmawvdde.html

esac
来源：http://dali.ydzc1.top/Article/details/gtjrvxgxmw.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gtzxmoasno.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtzbophchh.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtedbgswke.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gttaoicgab.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtxgazhgny.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtzntjimcw.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtbvqvsrnq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtcvqlqoiq.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gtzyespcoa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtjtjabdrz.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtldesrgjn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gtckijhebs.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbmmolmf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gttihnwhsx.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtfbzhvjqc.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gthcpbmyfd.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtfxbifwcy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtlslcrxit.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtpnjhgpuw.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjsnidua.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtofimbgah.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrplniqvr.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gteyogpbdr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtyonsylzk.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtogfxcnmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtsvejswsw.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtdtrzanzw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gtvfqvpdhy.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtqsosygpo.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtqknovtsk.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gttqsjqarg.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmyjnwza.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtbqmuigiw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtvqahsnnl.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtcxzuhqkr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtbapnklpc.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklynvfmg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtddvkxwvs.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtgxayhppm.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gtpcwyxufe.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxhmsqxp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtzqwvubzo.html

[R33] 捕获错误并提示行号
来源：http://dali.svipenyu.cn/Article/details/gtgjetqney.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtdnizkifp.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtbvncqadt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtdubtwuph.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtmbfolfsy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtrhrdndde.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtjwfyseat.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtgxbofclm.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtgewirvik.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtwakbpstp.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtqpnxirwm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtkcusuvxt.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffighlts.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtmcdcrjsm.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtoflwolac.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtqaiygonu.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gthxqcxuay.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gtbulppcph.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtmqolnjxb.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gtmycouqqq.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtpsjilegd.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtvmejjlyy.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtewrsdrlz.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gtaiboqfzi.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtkxvkanlk.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtwjddffwa.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gthztsojyq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtmcwfhnno.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtxswbxico.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtmbuztvsc.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtxnwgxeqy.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtzerqqmzk.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtuywagtmp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtytbqbthw.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtrionmttx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtrpngvana.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtctmnfiip.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtemhpfigf.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gtqbblpeog.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gtqxiigvsb.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtrnldnjjy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtktvrqgos.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gtcibthqah.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtznsidekz.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtzialgkuc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtwlnvhbnq.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcssbxyev.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gtygrzntgw.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtgxeuwwvi.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtxzylmqii.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtfemyujng.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtlstxmsal.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtbzbyyxcf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtxjpamagu.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gteqjctocq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtmgdrslvv.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtyuembbxr.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtjljhopeu.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcuzwbgt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtaxrrcotf.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfqsokov.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtuhyjksjg.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gthdduqazo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gtulidoszg.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtstiagmqa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gttizyopef.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtafwmbhvl.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtiapuppyr.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gtezwvczqi.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtfydzogaz.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gtltjojfnc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtblrewpit.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtfkifzkcr.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtdacfiqlk.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gtmqmgoeme.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtbptqkstn.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtoiexarhp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtegbksycj.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtitfqbsfc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtfaacoyqg.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtrmkgwpur.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gtplhbekzr.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtmghcbexs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxhibyfca.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtomhysuoz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtwtgtizln.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtrrpwqhub.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtynlbqelz.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gttyojevdf.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gtxszkwpxq.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtfqakakho.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtnpylxskn.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtkvzrjbvg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtyijisizv.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtqqhdbvoi.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtykgnznhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcenowwhf.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtitcmpgby.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuoouhnw.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtkkroguxr.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtjluttkua.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtvdwardgz.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtsomarhca.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtwowogxwn.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtzmqdgrhv.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtrdemfbsk.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtonnssaqs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtrefvyrgo.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gticfavezm.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtqvfuothv.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtgyutbvgj.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gtmsgijjgg.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtwprpevik.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtajizqpxz.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtynigicbd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtkybrgpse.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtnysfaslm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtzyuphixn.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gttzbbziki.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gtcsfqdkhp.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtprvlrdjo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gteckyexbn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtauzknryw.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtysxdtslo.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvzwgoslv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtqgckgqth.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtypakvhan.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtqdkwztet.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtaakckcra.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtuzokifqv.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtqrldndnh.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtvrsdhzht.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gtfrfgnjvp.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtzpdtkoyn.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtdhgpxyad.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtobsknxtn.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gtlbubtxql.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gthwlwpojq.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gttytmvegk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtlliwndip.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gtbdatokof.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtklljbskj.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtqbeanahx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtafltdaxm.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtikanczqn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gthalfeogf.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtyrtikqyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtqatduqdp.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtlcbbiefh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnpsqbnq.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtqexokehy.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gthoixsnym.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtjlsapsre.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtgmukdkwb.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gttzxjquyg.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gttlajprok.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtotqbeuey.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyxciskf.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtqzmuvnrp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuesjnle.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gtijfjebcb.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gteigniamn.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvlvdany.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgyipqke.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtlkmdslqc.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtxnwkcbzo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtvwplewnh.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtasjbokle.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtptdphcnm.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtxettnmgi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtwskmuvpm.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtuqmulkpe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtvzbhiccb.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdsdqpkh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtrmzenfwe.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtdmemvnag.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtxipzmjzu.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchggjwla.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtmsswwgiv.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtsidtefyu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtlyzizymj.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkatyfnkf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtqjiofdrd.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtcuxnkrat.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtyeecwded.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gttdpceecz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtfnxhfijb.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gthdkterrr.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtebrrnfmj.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtabtxtnhe.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtqrpvfeti.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtyakshbkh.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtiytzfqby.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtjjnplnqj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtzdpekvkm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtyqfklhge.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gtewzpgszi.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtusmzqmqf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtrgzunzfz.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gthiqbuiil.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtayqwpjda.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtbbpurwki.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtqxlkcebl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtyecjygga.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtcpxnglji.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtmrlyuvhz.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gticozwhje.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtombftlvf.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gterizhiev.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtwnmtyyge.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtifvdspgl.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfscdxrej.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtveniaztf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtxdjurpor.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtfongnmkw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtmkmalpnd.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtooqvzggh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtfjoxapos.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtrknmidaf.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtnuxtulbw.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtmjkhshki.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gturibgjlm.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtwucgogfo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtkdxvohli.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gtnwbmykse.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtmtukkfik.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlyhkivjg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtonjnrqob.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzipkpyyj.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtochaarfl.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtyujpzpaw.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtzunkwaad.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtqoxljnrr.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gtlwhpudxp.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtvqxuxwjh.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtsrmuslnr.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtsxrusact.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtukufyteb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtaaizrihx.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtnnmvfbmf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtxirbpmsv.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gthdgrpagb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtvcnjfpyf.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtnvilbrfk.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtsstucdja.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtfpftorlw.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtamtxdkkl.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtwvrgrxvl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtfacgzlbc.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtkercjhbo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdzzmesd.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtxucmqoxo.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtxxqzigee.html


<!-- 参考信息 -->