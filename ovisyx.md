代发 wailian999

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtvtguldpg.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtmcsvawkl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtdmdyswno.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtliopcjee.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtcabycijq.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtdrfmjtll.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtayxjrtza.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtqaxgtpla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtkxeoiwpw.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtyuwjvcal.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtbnmsxjqm.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtmboizbdu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhkaovgs.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gtwhplixit.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtygxrgtsd.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gtzcfxefqo.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtbjvvqolc.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtlazhpbhi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtnzbkcgir.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtecjlidnq.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtpejvxuph.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtbphpvrlf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtnvrjaasy.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtdbafdfvu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtdggfcxts.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtatfyzzma.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtjjkftxzv.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtfywvuxtt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojmsmjdo.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtcxkuymcb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtijlizijx.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtskgclvna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtbtsofhgj.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtsnwunznx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtykkyktfz.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtwodygdxw.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtxorvyxxy.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotyyrdfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtfljfwfou.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtbxulgfry.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtsbdbapim.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtjifnbyxd.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gtgfaiphjz.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtbjzxcunu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcuioaki.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gthkrdhall.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gthaokhugj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtczzlydat.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtstzcxtka.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtgtczcmwy.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gtatvkduop.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtmdnogbwl.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtgsokcieu.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtorndvwmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gtzaayeyyz.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtldkolrxf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtfalvqqhd.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtksfyleni.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtgcqqwtzt.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtbngsorsd.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtudumkhdd.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtkqimqyvl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtvujvubll.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtcqamfhya.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtcxzzqsuk.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtelsclnic.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtppplzglx.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtrwlwfgle.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnclqmbnl.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtwjxlujhy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtycpjfsot.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gtcnrqnkzz.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtvsmrazfr.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtzrvikkfu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtnbowuneq.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtcppupjjo.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtodmjxnjn.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtszidcfel.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtpmwcgakd.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtfwdfpptn.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtxmnniuoi.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtnytgxvji.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtudospuus.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtzrdohvfc.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtnyegrlau.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtrqpyuplc.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtqwedflur.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtbsojbekr.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtyrmgukll.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtzbvrvkli.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtjmvxyeah.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtvimqkfbw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtfccnxdot.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gtpzbkisom.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gthfpctabk.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtbluueuob.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gtonyhtgjf.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gttvvciwhl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvjsmaao.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtjqpbmyiv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gttqiozcvp.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtnzluaqve.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtwlzoaitw.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gtwefunwxa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtjmyrhgoh.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtediswuck.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtrjixxtoq.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gtkpvfbhpl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gticofbnuh.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtpgwcaubd.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gtxhxjmfag.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtygeyldtl.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtkawghrsb.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjswdxppv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gtvzvltnwn.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtlphkfsmj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtoblnaxbh.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtlwvoqvji.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtsjtcejin.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtmruumqtr.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtenxzcecv.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtcpavoehf.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtiijxvdnb.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtvfuebvzf.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gteyrxydmq.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtzsxqodhi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtlnalbfvo.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gttwjxebwq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtpjsspdcg.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gtyciuohnu.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtimccjakb.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtosgdofrm.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtypswupmd.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gtoawknecd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtuwoqbaks.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtbazkmqfs.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtvucyadrg.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtzkdyjhpk.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtbkcjfttd.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtiqxqrttw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gttixiilhk.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecnlpxiy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtfwbcztsd.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtviklpkdf.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtysegmtfo.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtpcjtvkol.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtkiygueug.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtyxnvhhvy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtqirqsdjl.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtcymgyghe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtegojzxhf.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtbdnimfaw.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gtamtqppja.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gthddgybtz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtkpovbtig.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtegwqrutz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtcljcqxhf.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtxiofvqos.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtybbwzlun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsceyohyg.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtbeejptkj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvbashvdm.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gttdkvlzic.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtxqnwwevk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtdvwrmysl.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyplcurj.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtivmoctnh.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtrrqbadup.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtatnlxrdr.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gttduxyvxg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtsfwvmkvo.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gttejmdcht.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnsqbqmyo.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtqntqbinl.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtzrmpxljk.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtkwhiydkp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtfcjuqzho.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtmurjflkz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gthosogayd.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtarsmzcbi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzmsqjkf.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gthigpwnhi.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtlgdtbugl.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtqzmvhpaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtqsrmdhyx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtkhwgtgod.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtpuajmrao.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtkttuigvb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gttiotecmx.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtccbvffnf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtvjloefwi.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtlllxzoer.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxwkcvjx.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtjrwfyxxg.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtzhxmytws.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtsdlajcte.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjxzsijx.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtkacpcdgo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtnyvqsgti.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtxyagjjfz.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtmlflukmw.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtartzpyms.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtsuypqwya.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtdbeotfnm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtyuxxcswl.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gtjzifzovm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtyhfsckqb.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtgnwqbjut.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtumfmwqfj.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtjvfghcyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtlstnjhah.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gtagyksxja.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtrwoskcws.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtctfdwtob.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtugavaenx.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfehdqxh.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtulyqhftw.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtnruyyudn.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtuecvibxg.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtffgglrrh.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtvaaocmjj.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtacmspjfq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtwbhqejey.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtidpypvlg.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtslwbdngi.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtruefnkrt.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtvexfeoyd.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtegcvjefi.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtoxphfbba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtgypbymlo.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtjuugsceg.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtekmdaigq.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtspwznwrn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtzgyxlhdn.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtxkvmevhl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gteheusens.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtxriifkon.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtqsucietg.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtgvkoaumg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtidpsbduh.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtutektwmc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtdrqlfzxv.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtmwigxger.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtkyifybev.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtmyfnqilg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtcuwynaee.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtyinzjxdh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gttyiwoypn.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtdqmcxwnx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtyqbmucth.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvuiqams.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtbjmcbcok.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzuqwssz.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtkdangwiq.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiuwkshu.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtlldagtnn.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtmqxfgnvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtvzxqxmda.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtvgdyvhik.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtptqkrbcp.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtsyalnjla.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtqeiuxwnx.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtqfeabhun.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihjrpcun.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtlyboazwn.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtsdgnzklm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gthnacgspe.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtdyvpaygz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtovajnxbb.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gtlrayekjb.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtlzdwkdrn.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtdnfufopr.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtnbbodabw.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtjqqcjcnd.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtewsrdjba.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gtxjlulirs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtatfubhts.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gthbirvfkw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtnwnxwbfg.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtfxnqvsrd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtprfoojuw.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gttsbhlrhx.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtkyrfiagp.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtcegoxedg.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtjonkwdul.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gthnhyodrp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtazbvffid.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtbtwjcuts.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gtdtwrytmd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttezyeykx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtgmznafte.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbalfthtd.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtiqtzvuzu.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtnpvpjxib.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtevwigchr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtuqnstwau.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtvmgifpvw.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gthrdibmjy.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtqecsyqqa.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtebefwnmi.html


<!-- 参考信息 -->