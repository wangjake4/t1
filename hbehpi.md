代发 wailian999

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtoozxkpfu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfneeksvf.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtdpmazmbz.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtquyqtawj.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegdognqa.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtcuudrrqd.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtptpdbyek.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtwduewxpm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtoekyxwud.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtfmmlcjpg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtdtkdymgt.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtpqyabwgt.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtyfkngogs.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtwxeamatg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtiwjwcygw.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtnyyvurcj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtyzvidjbx.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gthtmuwsoc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtrvqtfmtd.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtfpcybupy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvwwdbcd.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtfbwvouhu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtpulkpbmn.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtflhstdny.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtwihggzfd.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtlgrtolfx.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitigsrte.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gthpslvtdd.html

esac
来源：http://dali.smart0.xyz/Article/details/gtjilrcqfx.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtmihnxotu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtxknchlac.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtalmuaoyy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtgiqowyif.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtgulmgkzt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtmbqiwwur.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtxqwxlsyp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcoieicqw.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtstilprvf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gttotqddlx.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtlqyzpibx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtmjphrwlc.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtwmkgypqx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtuxentasu.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtkmvwyrgz.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gtwnwdinjj.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtilgirrmm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gttyollkfe.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gthokjgomr.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtffzavdjv.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtgtdrthwy.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtlegbedxu.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtusbvpkdq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtkqvcikhu.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtqncioqwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gthhhwmhml.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtauqxtmuz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtdpckpqix.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbklkpczz.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtffcmrrzw.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtnnkykuse.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdkdtpld.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtfafgmuml.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtqzmxepup.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtixtyfpmz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gtxbbpsecu.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtrzlmfewu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtklgrupbx.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtejwkhvno.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtzzwuyovw.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtijzftjnw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtrelzmklx.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtktjxqiep.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtgegokayy.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtlumzwhzj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtfoktcbie.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gtzfeoirxr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtwyhcirwt.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtmjlmgpwv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtwtcivugz.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtvtxvgtpk.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtxzxnpmtz.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtbhmsdtfe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtswlmnato.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtayuqnvmr.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtqnmdisup.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtvegvhxni.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtdobttfrj.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoicmsztv.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtfskzvkum.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtwuoinqjt.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtixlgdgrf.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gtrwpuutwk.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtpkseirrc.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtkbuiqcmy.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtpchpznlw.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtbztommnc.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtbwtferbh.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtcuamcchu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtxjlsgeqs.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtamofckiv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtoyoschnl.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gthsjokhfs.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gticaywsxe.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtzdmwpffp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtawqiqeka.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtaqorizla.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtakfovoqm.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtafmxtooe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpjwvfhb.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gtqcpzggww.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtxasvcoav.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gtafqcniaj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtiubtqfxy.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtxlbddhjo.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtyjmrqmtg.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtnuirpvmo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtjbzifehe.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpndorjyf.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtpmtyfhig.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtmigvifgo.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtkhljbydm.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtbrhcisbk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtunalsync.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtptocubfc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtzfkrqxfr.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtokfqchjy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtjcmybrcw.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtvkurkhge.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gtuswmqgeg.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtuimzsrhi.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gthomqnlno.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gtlfpnhfao.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtxzfdqnym.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtaoiwxtrm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gttapjrekk.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gtedftsikt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtdmxjgzlk.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtexarryxl.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtozscxegd.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdpeqyng.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtoxthjkxf.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtcfgkkswu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtezeejqyo.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtsysmaerc.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtusjstkib.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtivwevmtn.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtybfvhzza.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtemsiiclc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtkvqwqqie.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtghjzqcqn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtcjlddybk.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtvstujhmb.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtqnwvurxk.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtlfdxtyxo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtldikjisq.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtdzqdqher.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtoxdorcee.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtdvaupjdm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtifcxmrpr.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtsanxevpg.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtdqqscmbp.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtuitfycxk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtsfhlyqff.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtackwctgn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtivnajwau.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gttnxhzwcd.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtoucstbmo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvsllpsfy.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtipqlgmcg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtowbgrzkx.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gthoqavqqz.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gtsajjzbvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtvjewtopw.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gtoacqflwl.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtcqldsoff.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtthpxsrtw.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtkazfegkk.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtecultgmx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtwghmjigi.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtdmxaceln.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtvzxcsrzn.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtlcisabqb.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gtjsuijzzn.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gtwmyqpkyo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtkopzhwcc.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtnbpemqwe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtgpczbrfu.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtrbvgnoxc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtddxrltjk.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gtvwtwunzd.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtixslfcgu.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtwgesxcbf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtcuxmrkre.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gtzlaxtuya.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtzhzbcylr.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtvppnfxqs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gttbyibjju.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtazwnknqc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtonhtxalu.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtqfjihyak.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtxblherzr.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtdtwsfhxz.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtlsyvvdft.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtjgvcepdo.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtzzibcceu.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtchdhocml.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gthmyornfg.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gthlndrtof.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtptsyhayg.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtvirrjpps.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtxuddddjf.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtpruqqkqv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtnnydhbkd.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtcfccuhqa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtygfoptlj.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtyiehplip.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivqtsmtv.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gtrpiiggde.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtrlgmimvs.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrglfqjym.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtfnmpxhzb.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtcamfzcrb.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtudaahcts.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtvajzvazh.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtrtpycrio.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtmuzpuzaq.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtdspchpon.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtoctesljl.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtjafzjwfa.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtntwzncrq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtlmadianf.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtkbnttkhs.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtymakbtwl.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtczcsqfey.html

#endif
来源：http://dali.iojbl.cn/Article/details/gttcetzbyw.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtcdeojbjz.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtuzxscuhu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtqomaejmu.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtbfpoduah.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtxuvhtgsg.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtymqswwrm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gtqihkokwa.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtqekkdjwa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtqkvjhxvp.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gthiuejyuv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtgzzcaaoy.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtqghwbnro.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtucizfuqp.html

[S37] C++：set
来源：http://dali.cucudq.cn/Article/details/gtxxxgtimy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.316326.xyz/Article/details/gtdhqchrdu.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gthapdtahn.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtvixbneaw.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtqmmojtot.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtxgsehuqp.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtetkzcjjp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtsqhqjqnv.html

[S41] C++：类与构造函数
来源：http://dali.nwbrower.top/Article/details/gtbeorjpwq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtimhfrnqf.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gtlpbosnpy.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtnerfgmmw.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gthfkmrrsi.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtordbtmku.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtasatcgea.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtwydjniqv.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtyxjkccam.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtxlhahgal.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylzroaej.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgvlxspzs.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtuutzivyc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebsbblgg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gthmqdgpty.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtyfdrzyvr.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtczdacdzk.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtayywomik.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gtgpctiydl.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtjbieiazr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtygxzgyjq.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvfmtlhp.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtomowrudn.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtikrokwye.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtalmdnurd.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gteiqxqcbs.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsikjloqg.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtqdwvcbfp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtistqaxmd.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtgpevfwnn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtfuvnbmlg.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtiuswhtzj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwzssibdw.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtaqbxbxrx.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtihjqdfwp.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtdzsrnlrn.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtmwgdrgog.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtjiqpmdli.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtpovhkcch.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtzdzboqvg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtriifilew.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfjjbmtib.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtrmtzcqtm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthgzfcemt.html


<!-- 参考信息 -->