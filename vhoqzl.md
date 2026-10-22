代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gt2enhmsktg.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gt2tyqfvxth.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2prtinnye.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gt2knzvxrgn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gt2ivudrewc.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gt2topsxxmt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gt2cbembjlb.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2gstruijn.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2ffdizghg.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2cteyduxd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2opekvknk.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpzhxubi.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gt2urtnslvh.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2rdtktzke.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gt2oyrfdgks.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2rjqbxeqa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gt2cugegzns.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gt2fbvzdqbc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdudekjp.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmlfbzlz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gt2pjjhavhd.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gt2cgzxsfls.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhbjfuql.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gt2fhpqnstv.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gt2todlvdtv.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gt2ylzwsaky.html

echo "scale=2; 10/3" | bc
来源：http://dali.hfpthk.cn/Article/details/gt2fnmyqtkz.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2rhbppixd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2hjblbluq.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gt2knhejdxr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2byfrwmnv.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2xqldalmi.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gt2dygfzamn.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gt2xsysedex.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2vyknkyuz.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gt2qhwtgbzw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2zwydtiup.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzpbycq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eimtkewh.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gt2gwprqfpy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gt2dpwzaugr.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gt2hdditxfj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hviztgvs.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2tqstxcvn.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gt2yxxucukj.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gt2utgrvbdf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjndppjf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddfceoqg.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2fdtfaqpj.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gt2qhxywwvr.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gt2jqpmlgiq.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vprgazdn.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gt2pmybudgc.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gt2msmzsxnu.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2otriwllt.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gt2zznfrncn.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gt2hgiohkrc.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gt2isqrizao.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gt2ixrgmfhv.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcbpirvm.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbbepvul.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gt2veaywudb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gt2zkldtgvk.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gt2dsquaaht.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gt2jzlzotud.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2ottjrvcc.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2fephhwji.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwbmhgis.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2lpabxtxp.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gt2cdskinjn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2exnzmgqz.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gt2kohmrxll.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2dhzpmhup.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2iebiyfrt.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2fitkadhz.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gt2hxbmfrqi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gt2wanycpyl.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2luntzqdm.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gt2wgbzvwge.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gt2faovuopu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gt2wbefivnn.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2lgejhlyj.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gt2qzwsolbw.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gt2yhtdfjln.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gt2huzxglse.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gt2qxlkzjvp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2gijvxdzl.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyhwanep.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gt2qhjlbgcp.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2zehlbusp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gt2bpkcnazo.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gt2jmkqysrn.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gt2uuqvcoez.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gt2fchyfryh.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gt2aldlggxt.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gt2gmaqnrop.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gt2klbrxltx.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gt2hehebrat.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gt2ntpuscje.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2zvchejkf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gt2aitlfuqa.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2riyxxklm.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gt2dudiqigx.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gt2pyluaqdp.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcozwwyh.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gt2sjujsgee.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2mfdccdke.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gt2kgshdszz.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gt2zvxihcyi.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2ocvsodve.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gt2cndoagyx.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2ljytmyej.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gt2qwmpkwzx.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gt2bileuobo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gt2tgraejan.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2twgtxmjn.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gt2fjhwuhhz.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gt2nllssfgx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2jezncsgr.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2nzqljcdx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gt2tsclrzvf.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbyvbsup.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2lrssukxa.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gt2zhoobhii.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gt2knkmbvti.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gt2qmjbbkub.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gt2sqzhptzp.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gt2zknqjzfm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2bgcqjaja.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btifmflb.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2jzzvtfkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuhmmww.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gt2echuliem.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vgjyamlt.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2mbhfibbh.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gt2ijcnxvui.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gt2mvuvcjnv.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2ofjceser.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gt2trafpklh.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gt2fvmcvzny.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gt2mmqwdqti.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2tqvagbes.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gt2nftjowug.html

[S05] C：字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftrjnncr.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gt2agyopkln.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymevazma.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gt2qajqjxpc.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gt2ydvmfobx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2pewvfoky.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqcurakl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2vwcdlynr.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gt2beiitfta.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gt2msijikbp.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2lumowehk.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2fxrdirke.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2zmwgtpyd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gt2epvwskvf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2qhyizlgp.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2etbcsgoe.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdpdsicj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2lvwmthep.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gt2iikaqzqj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2hggwinjq.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gt2pmuxqbau.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gt2gsxxowgx.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2boucddpz.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gt2vmoojgmx.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gt2cibgtkzm.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2fktxiiyw.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzqnjkhu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2codgobbt.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2aqahawge.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2fqgliuir.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gt2yyfzktyf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2oyazqjwj.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gt2nugjusnv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2hdqhudda.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gt2dzrfqigh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzwevxj.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2deqjejda.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gt2nqcctezq.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2hexzacic.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2lxdjewbs.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2exjocrrq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gt2adbdcain.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owowsqbv.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxxhnpcf.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gt2pdinxtwp.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gt2sffurrzs.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gt2ykewuhuj.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2paxruzkw.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gt2yxxnveid.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gt2cnxbjltm.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gt2skehybjh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gt2fgozrxpy.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gt2qkeqrzxo.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gt2zwptehbj.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gt2dornlhvv.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gt2hbtewekv.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2ffbwomwp.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdgscwjj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2vmwuuthq.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzekfkyd.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gt2rfgporer.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2lygjnqto.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxhvpexd.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gt2gvewgegk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2djniqkwo.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwnkuyls.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2djoqxtdf.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gt2hksztnsl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2goxjhign.html

[S37] C++：set
来源：http://dali.cucudq.cn/Article/details/gt2gngpozxn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gt2bpmavgzf.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gt2zhlutyan.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2lcvtitpy.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gt2iovwywjh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmcqfrft.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gt2hrhphleu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2jalqkyeb.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2zgpdgwfd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gt2yamblwyw.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gt2usdpfwfp.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gt2xtaqnpvx.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gt2ytrwhgvz.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssgdwldr.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gt2wkgnoxtf.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gt2tabkekgq.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2iosurebn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2mfeinylf.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gt2zahfdyjd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbbbnoga.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gt2eiibnhdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gt2knvskyfd.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2uafzajqf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2uczamzxb.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gt2zrbbwgnz.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gt2sbdbprxu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gt2mrhduptx.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2tgqnutpj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkjblzso.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gt2ipbhqivl.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gt2jwowbpll.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2ucwzppsb.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcngiszx.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gt2ssxnugcd.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gt2dslfoeor.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2whpfhmqe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ruzwfemg.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gt2sfvvcmvq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gt2vbcyrvmc.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gt2zgnxalvq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gt2pxdjmjml.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gt2cervsabb.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gt2kjazyoik.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2pmcilurc.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gt2shsbwqjz.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2rzkrvaoy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gt2txlveeyo.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gt2rbzxeany.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfrxuwma.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2owzmgpaw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2hoptdtgx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jiubaana.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epismnip.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2wsllpzcq.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2smiuloik.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvgonvrs.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gt2ryjvlsuu.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2syzgjdjf.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gt2pztglbyn.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gt2piwttdlr.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gt2oiyplnff.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gt2ztxmmqzm.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2elbnkgqv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2pjudjzsb.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2fsgrbrzi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gt2kapjjebu.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2ipvafqtc.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2kgbkacaz.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gt2emhupcal.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gt2zozsrgyu.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gt2czsfxfqc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gt2typmowii.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gt2vytljexo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gt2qfolsxln.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gt2dhxllwno.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2jwtdlgfs.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gt2ohxgtrqx.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezpyyrvo.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2ccnpekfb.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gt2bsftbmyf.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2cpfzxurr.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gt2beuowppn.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2uvntovnj.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2hpirgoru.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2xbyxpsrr.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gt2nfogzqgt.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcksdmgs.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gt2jshovwwr.html


<!-- 参考信息 -->