代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtdthivrhk.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtkhkyihqr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gthcbolpkd.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtscwvzihk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtmtasclfd.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtbhwajgyw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtdtqurvav.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtjxnsojzi.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtunxcceot.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtnbdcrgza.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtbtolweea.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtylynusrf.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtsdooegxj.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtgmffbcah.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtppaywdvv.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbnsxacp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtwtkatuyw.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtfavgevzb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtbyoubnpj.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtqqtaoqas.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtcypzqoln.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtezvmuelt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gthhvdaffw.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtcumektgw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgfhihhe.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gtirqurznp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtwubakzrf.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtbaadggdr.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtdaaiknik.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtdefneous.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtivtuqtai.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtbndijysb.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtduioyswn.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtevoyehhc.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtmyohlltn.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbepatvq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtsglmarai.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtlvtcztqp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtpbzolwwz.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtsllttfqq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtjhxvbwsb.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gtfgvdmflx.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gttaymtipx.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtcimimcnm.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gtyjjgzyjv.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreedfmfy.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtcgwnqlds.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtkmqhrnjs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoftnmdqe.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtrqaaojfw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtjbijhnkx.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtomlbloua.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtaqugcjoy.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtaemyovza.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtqjgmtrtv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtqibmcbpn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtchvaijdz.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtbcdoldfe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtowrmidxj.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtwakhcfeg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtkzeafcik.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtckkorowr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtfczrvolo.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtjfcfyjgp.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtiobauxmh.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtujitjiyw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtpeeqrstk.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtzocnikfv.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtpnvtjpzi.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtxjkxbimp.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhwbmwze.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtzvdmrwvv.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtlifefgdu.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtgzxiizbu.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtdvsdwwts.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtagehobcr.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtvrfxakml.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtkdwylemb.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtnkypaebs.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtrosrvifk.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtghhqhcwi.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtmbxgersn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtotptdgdm.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtqtjdoebi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gtvnloccyf.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtclayaybj.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtbulmzgtn.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtmswysnke.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtjfptuiai.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gteilmvest.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtuijqynmm.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gtobbbciep.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtyzwsbhzx.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtdbifolqt.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuisyilt.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtewccmolm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtqujgvmtu.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gttawovvsy.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gtagfugfnk.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgsfdjyy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gthiplriru.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtrhsmxpns.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtzbubpvze.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtplysmvsi.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gttxavvnpu.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtjiszxnvd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtwxfrewnp.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtedkpfgwv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtfklwougq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtwefnylgy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtnahtydza.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtmjhyrrjo.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtwzhugain.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtdwpbdicm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtnuenrnej.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtodgqgvfb.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtlyalqagm.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtyhycsyuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtavkntefe.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtawqshmdq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtghghrdwn.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtaokbvcpy.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gteerdhnfi.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtobwqqhll.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtwwainqcb.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtcxfqwjwa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtzojiyyrv.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtauwfwzlk.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtqxasmhut.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtofepryew.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtbddjjzzq.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gthqnnntks.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtmoyukvyk.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtwyvykbli.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtselmdmsj.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtcnwvwjrq.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtremkwrgz.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gtuyctbafx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtzbeokfoq.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtofpysosg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtkpwmckur.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyaezgcj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtntxcpeoy.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtfwgydowr.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gtuaxipfkp.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtztirkync.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtuavxnzgo.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gtoypobfud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtjfhrwhrv.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtflrocqad.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtwujqqdee.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsqdxugoo.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtnrjhfdok.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxandgmsi.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtapnothke.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtkcumenig.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtguaspvhv.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtkbgtdkoa.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtlbvjuxji.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtbjqhnqnz.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtzmuaobpc.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtlnwssolu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixvuhtbv.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gthtjgsmsv.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgpczhuu.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtwycqnmqe.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtjgchqpvo.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtdiivrhde.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtfeuymanc.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtzdgvxbdu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtaqefucab.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gthdbzbvto.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtfehewray.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtbzmfwdlo.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiteaacpa.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtyqekyczx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtzwpokuin.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtrenujtjk.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtphbyxqnd.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtyhfginhw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtlcchnipo.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtxsadcdkg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtikaoyypu.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gtidqoegeb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtvpzvclfj.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtkpnodapq.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gttriaglkv.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gtvfsqahem.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtmzfmqohx.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtvrdbrsrv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtrgxknvkh.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtsurrxtcs.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gthcqtvpve.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gttutzroil.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvienrug.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtaxgvphhm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtnlodhkjq.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtmodlkdpg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtacujuqqb.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtaxwuuflf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gthgnrqsnp.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtzyoqrclb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtcuyakqfj.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtbzuvljbv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtzrmmpwii.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtimgwpdhl.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtuunckicy.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gtzepubtan.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtuolkfbzt.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmclawsq.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtbnbrarkq.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtbvarycqv.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtdyqrnswp.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gtjjnmgbvy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtqlojvdgx.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtxaajvpjc.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtwwuyctcd.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gtugckounm.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtzybltzpk.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryostdej.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gtghoigjpa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gtmcrbaqda.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtsssfezxx.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtmkqchpfa.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtwlsxbhfc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gttqhtioaq.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtdktpdhsy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtogwdfjdd.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtbxoresli.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtohhciekw.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtgxqhbtbl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtafkantir.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtmxtwfkif.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtrjgspdno.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtbmtgkjqd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtstbdweqq.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooorwxtv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtwqosjtna.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtfeywqvdv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtrkgbqcsz.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gthdqnpmqr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gteoegyzmb.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwriuftjn.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtgoqimfgf.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtdfxlpoxv.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtgfywljcy.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtquscbbhu.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtdjuvkmjq.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gtjylazbby.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtciivlect.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtklbutqth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtmvivssjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtchxxbeve.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtxwgwtdmb.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtafhwdjph.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtjmemdpdi.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtnkoltvmi.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtzzsjbbds.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gttyrkektb.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtqmibfrao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtpqueogoi.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gtveljbfwb.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtbuzrkpxb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtocymmjao.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtfxwkymym.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtxpntpnxl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtxrrvyruz.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtkgqhpufj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gtqjsptama.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtovfatgba.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtwyvtigio.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtewajyjpa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtbsfxntsw.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotxvagaq.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtekhfqgra.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtjfilmlxl.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtxvawvxmi.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtfjmbwxzx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtygjtegkl.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtlzyiottc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtzglczlao.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzhtuhjcf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtujjqybuq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlbczafek.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtkoedrvnc.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtxlyuoluu.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtaszrobvt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gtiqwsblfo.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtydslnbkr.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtbpciboxe.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gtnkmznyyy.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtioyqjwnk.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtnqecluvv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtvjgjxqky.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtpxeyttvc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtcwusocix.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtwzalhqhz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gtprnazqac.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtfvbchfsn.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtuodfilnj.html


<!-- 参考信息 -->