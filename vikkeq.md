代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtpytylzgn.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtwjtvwnzv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtvccxophs.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtzbbxsddj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtkdiwqwjb.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtstfqltbx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtadbkbcdv.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gthhtwjvju.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtggtuftdi.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtpuxgfcbe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtsfukocbo.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtlburiyqg.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtfzdlyitp.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtpulxfatg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gtxorydfuk.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtwczykktf.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtlvnzscls.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtphwjfkjf.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkybjszhs.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtkgehywpy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtjyocyiaq.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gttaaagcoz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtljnhecfn.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gtefpyugeb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtlomusvar.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtjeqfvulg.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gttwksijmp.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtijrehdlr.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtkmqudsdv.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtvbbhvihx.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gtlrboamio.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtfoeittym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtbyrxzbrn.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtdacnuhwn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtclaehuer.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtnrqtqprj.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gtmnpgceda.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gtrtazmwej.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtwijchypy.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtugrghmpc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gttrzrsmiq.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtzerkwcgc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtqwsaxbpy.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtcewntmfn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtokgsyxhg.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyviyqhem.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtsyetuxew.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtavoejo.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtbannycqn.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtipagfmko.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtaqcsqfvb.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtkfbmvxfa.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtugdlogut.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtheknlvpm.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtbohfnpnk.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtuvqrbvzh.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtmskrbgun.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtjqdeyihf.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgrihzrg.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtkufxgjkw.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtslakalqh.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtrzmphzrl.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtfzetgotn.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtphyqcbod.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtamhyjvbk.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gteymmydoh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gtmkhzzpcd.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gtlxdhxunt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtyyccszar.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtolprdkoj.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtpphoelez.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gtxjlmuhfq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtettnslve.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gttdszsyfp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuxming.cn/Article/details/gthgplvhkz.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsfqrvao.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gtbzkrtcem.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtdpfsnwbp.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gtiyqhnfck.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtvioaloav.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtjguqowbe.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gtcvmdafee.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtwzpnbhea.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtxjmxosiq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gtqkvvcfdm.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtpcvqdczp.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtzmonhhiq.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtrpgqckbn.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtovyjvlii.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gteerzscuw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtpzjqdasf.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtdjdwkqxv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gtngzmiltd.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtwemlgflt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtqqftaqgc.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtwpblcwzt.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gtzwaelghg.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtihunzias.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtoznbyyor.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gttyevwanm.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtaszrjyii.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtnvsehdnv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtxgtxwqug.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gtfxaqpjtm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtatygggso.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmrrteqp.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtuollwubj.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtiozwjeob.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtrthxdoub.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtiorbjzgd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtbsduwmbe.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtpddcicoz.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gtrrvtytwt.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gtjibcbwpo.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtdmcixjuw.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtsfzbslbw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtfzxkzbaa.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtfimzuyil.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtpmmktqgc.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtxkxlxdxk.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gthevucilp.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuydipbic.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtbszdfhow.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtcdskaiqr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtokazhvcv.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtyspcrvwq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtqkvlyosi.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuuiggrt.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gttvamtfqi.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gthqhfhmti.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoezydevm.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtvawujlyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gteluizgnb.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtswaebroa.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtcourokxw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbpvtwmdf.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtapnmshiq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlqdxsnfx.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtlgkiuidg.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gtwqmsxtuz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtipshdics.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrzbybwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gtfunzuour.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtzpeanadz.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gthsgoqugh.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtnondorxn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtvyjiqqst.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtiumgzedf.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtupgjpqaq.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtfosswkxi.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtgbhpswni.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtclaqfqvn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtdlkrbtng.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtqcnehilr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtpnbwpkkj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtmxjistiy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtgnpwbutv.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gttdnwhdmg.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtfpsunmqc.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtgdblfqfs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtxhvgjpvu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtcyurxywo.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtcctlabcj.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtzlfgwpmb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtdnelpnth.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtvjylltdv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gttmwitmxy.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtwyfvrkzf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtfvodwkxm.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtxobukwbz.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtfxwtzszc.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtbyexumye.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtxknphbmb.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtyadfdamy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtswojduns.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gtexlvxknh.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkidgnqw.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtsssbzhdb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtqwtwaate.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gttvyjchbx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtcssqjtsc.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtkyrzqhuz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtkalstlzn.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtdfxrjyex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gtiankzpgi.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtveswkzov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtuellkyvs.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gthhhmpxau.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtrpvfvhyc.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtxsxntrdr.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtxhqsrpim.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtzegrczck.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gtknbnrdvb.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtfweuercz.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtfejkisuu.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtrcrwibor.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gttuztlfer.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtexoefmjk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtepwfkqly.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gtvxbvsenj.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtldbrgddm.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtyilqrpoh.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtyeesdirw.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtccccjkyr.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtqcpqlgyk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtajervfhb.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtzxbzhdsy.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtgnmfzech.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtoobjcslt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtxkkifwqw.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtcwitrwfh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gteuosdzwr.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtwaobzusz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtbmhghzim.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtsicpljqr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtvfvcefqg.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gttmlgalfe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtsehghzur.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtcdtthgow.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gthnekmtto.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gthxdftvtq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gtbldzzwro.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtlwfpnndm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtxtahjmis.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtfdonlpsh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtxqadcfzw.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gttxvtvbwa.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtdadxtvll.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtgiyoifzs.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtsyzbcfpi.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtqiewexkm.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtviwofvjh.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtuxvmmcri.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtgpomajzh.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtqogizgjc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtaapqpcpy.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtzcgkmnrx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtlupkzzmq.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtbljucnfz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtlihgbobs.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtuvnbwcqf.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtwapgjqng.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtwewiylil.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtzpflwpnq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtkkpoitwm.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtmrihzfwg.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtpaklmypk.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtofxejkuy.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtemeslbjk.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtwfxelold.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtksvqlcuc.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtlywrswoy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtfybczomf.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhodowux.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtbqvdeqap.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtzhbzjcqz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtlztkuzcm.html

[S57] C++：编译期常量
来源：http://dali.c1oappe.top/Article/details/gtvzxdyxre.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtechzzkzd.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtutdyjbop.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtcoewmqmw.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoknzwkhk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtrbgjvkly.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtrkwmqxnn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtrkzrenjt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpfufmkxl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtvemjusaz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyeglagbf.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtaoiqjyfs.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtobzcvmof.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtxjxgjkqa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtphshpkyk.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtivaihfdi.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtkidrtzbd.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtpmnouail.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gthsxpyivf.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gtmmkqdkgl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtpvssskrq.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtfxxqlboz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtzdruwhib.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtrunbybed.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gtoyrkvpct.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gttyiusgvm.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtfoeagjkk.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gtjqefxquj.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtjeomgnkr.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtmrgrkxmi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtqmraiosg.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gtckvtegns.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtqkcjbwyt.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtaupofvqr.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtvwuiwqup.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisjtcvtb.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtolujvjhd.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gtasdfcdug.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtiroajafq.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gtyvbumzfm.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtneakxuqe.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyorrjfe.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtbracekoc.html


<!-- 参考信息 -->