代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtzxbluqzx.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtoackbzzd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtlrnzxpou.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywvtpigu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gthldwvpaf.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtsmdxhqtg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtqpzzrmfd.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gtmuntmxpu.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtzxpzkovt.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gthbjfosrp.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gteppmceoo.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtgaphzokp.html

esac
来源：http://dali.smart0.xyz/Article/details/gtyqgokygt.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gtnuyhxtzp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpslujtef.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtxuitkjpw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtknnrjcxd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtffojszwn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtzlnwvilc.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtxlknyfhj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtnhtevnca.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtazkwxyhm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtpaptlsoa.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtqfsboyuk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtupfkjmhm.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gtqtlfwqne.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtgnjdpzrk.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtawxqouvo.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gthtarllgp.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtcviaoted.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtikdmmvbf.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtxcmtjicz.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtolzhvaas.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtszwcizhw.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtaswlnwto.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gthdjqnsen.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtzrwpjual.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtibkdekmr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gthpkuhzzu.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtqftsnqnd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtctfsydoc.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtrprjowfo.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtqqzpmenh.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtxlgikfkk.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtveawpuca.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigliootl.html

echo "scale=2; 10/3" | bc
来源：http://dali.fengsongda.top/Article/details/gtihduuiwv.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtwocwnols.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtpulvxxmd.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtyaqqtqdn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtzivgztrj.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtwxcubqxe.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gthkgnhwnj.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtrruzdvkp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtawvnssft.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gtzhxoclus.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtwtpuzxkh.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtrzswommu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtgrcvvdnj.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtyiltkriw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gtdwvzrate.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtommkntbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtgrrbbocc.html

[R37] 把输出赋给变量
来源：http://dali.ivvv.top/Article/details/gtdgerhzgx.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtfoxfhhsz.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtzcyaxhns.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtgeabprza.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtazflcpnb.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtldxbbaeq.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gthlqtcxec.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtuglxndqu.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtcssiifve.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtiqdpoekq.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtbsfxdfwm.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtsakylaaq.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjgeobgra.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtxjfzxjsi.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtldpuibyl.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtfipkkafr.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtjhtrbczg.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtubqdaojw.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtoxgwewvz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gttdzsslfy.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gthsbsaima.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gtcfcwkdvk.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtkywjbvdi.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtqijtwwsz.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gtfezcbvva.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtiyzzliln.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtacqiugcw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtyvcqksis.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gtldcyhsti.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtiwoyuhyt.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtuvdblymw.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtdebiovcd.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtdzuatran.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtchezzqrh.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtddxieudt.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gthshplzia.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtdbuakpgc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtatncyntn.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gttvujnzcm.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtmtoahfic.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtevddujhs.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtfbfwvdhf.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtwdqbmwsq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtxcvpveyn.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtlqzvyaer.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbpvgxzf.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtqhdemnzu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gtbpckxjqq.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtghdcvcby.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtuuozysfu.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtzjqzszff.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtdfyhepff.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtpgrqxtif.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtayikedfd.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtgelqvmff.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtmcfjbyqh.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejlpfugz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtqipqrihh.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtbnshwoyk.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtrtdafzse.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjimszshr.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtyvtterlv.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtgavbobmw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtwqestglm.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtnkrhgake.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldzoobzs.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtidzzawja.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtoxexqzrb.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtxpinsjxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtdszzvixz.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtumqtbfdh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtzauurexm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtsidqctyw.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gtyubxkczk.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtzijsvfgi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtelodzmor.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtrcmeikmx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtlnirhnsv.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtftibgsft.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtlsgwxooj.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtblnosxex.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtupwfgkns.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtqkdocssw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtbcvszkhj.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtaadyqapp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtiqvjukgi.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtokfznzyo.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gttgmrxacj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhfnwwuw.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gtonygysul.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtttxhjwnx.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtegvstqrv.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtffoorjaa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtfizbtyed.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtqguovxiq.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gtjvouabfh.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtzhkwmcbz.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtfzgnlhcy.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtzadteqdi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtxeuzchyp.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtlbutoojt.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtyqatuxcp.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtmskgmjbk.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtzpabxrad.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtnthqeina.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtmrrvrmlr.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtncckwhun.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtuykxnoaj.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtsjjhqwwn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtbnuguqns.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtlmtrzwci.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtzptqazaf.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtsaupxdky.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtmpclpljy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtdhldlbjs.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtxvvkhqbx.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtmtsjcago.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtnqprierp.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtjzrifsnk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtcycyhaua.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtdihftikp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtfnmhlwrs.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtmiyqapby.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gthrjqyewn.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtnczkftfq.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gtopnujxtf.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gttjcjdpyw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtybktxeln.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtqjflhury.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtvakyiyen.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtuhfjuuqw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gthajxzain.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgehfgcee.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtigukihvh.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gtovspwofc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvydshooi.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtaqpmlifb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtttmsgmqb.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtxfhkampy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtbtgtcpop.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtfxrhqxjm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtkqbyrtnk.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtgcjikhnj.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtzinufbkw.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtsoyghytn.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtrqqaazmu.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtfepzkfij.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtofsxmloy.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtemukdbsn.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtzjgfpfdw.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtvmzzsvot.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtzwimyhqv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtdbhxdxan.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gttksonhnn.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtuanredof.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtdkrexlyk.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdlltxws.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gttcqssdvz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtufdqkbuq.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtmupxbpct.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtqubazwzy.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtmilvwyif.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtygrdhlsd.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtucgztgaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtdyvyscwx.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtvuzkjyxh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtjaiqedbc.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gtvqgaqzhd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtnbsrsmpx.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtdvedbvpr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtdbnmtzvo.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtepfwwxub.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtxzlwromi.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtrjnymvzi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gteposoekn.html

[S40] C++：查找元素
来源：http://dali.wangshuangyany.cn/Article/details/gtjkucrtyl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtymklvrvw.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtyhloofne.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtxsbkcbrk.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtqvzytihr.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gthukgvyyh.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gthbqijgrl.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtcnzgohtg.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtqldmrhld.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtdctetzsy.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtxeewfsav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shuidangran.top/Article/details/gtmraiaxql.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtalugzkbb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqxkqngpb.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtzkyqacpy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtubxuhqug.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtojtvnzdn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtoxmygiot.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtchimwhpz.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtpgtgvkpb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtevgrmzew.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtceixshub.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtbadtmcdt.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtccaaohwa.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtqndjraup.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtvclslrmm.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gthsakptoz.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gturmucbyw.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gthtkgagkl.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxdytglr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtdhqeerlc.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtwddmpylf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gtkgoctgmp.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gtrwkvtjoy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtstxepgkk.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtznhyhzre.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtffhhgsnf.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gtmvapduwt.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gthyomvhyc.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtgidvksoz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtriftusxk.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gtdvpxmobm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gtqavjccaw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlrwxusou.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtwdyfhdql.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtneerjgkq.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtgjunidnf.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtrqlhepku.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtdlnejiec.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtnfabwkdw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtzfxspigg.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtfilwlvhd.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtlmuuxmrz.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gttxeapykg.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtnsnerlwn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gtxdtrvrse.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gthjxbqgai.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuxauhpy.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtcziijvni.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlriufcqd.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtovkhbwby.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtvnmzgoki.html


<!-- 参考信息 -->