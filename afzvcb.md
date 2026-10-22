代发 wailian999

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnphzlld.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuscdgeog.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtbykpjvbu.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gtbsykyqno.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtftrdmgtt.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggxkibxi.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtjsuffpfo.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtbbtaswoo.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtannivrpy.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gtbkmeumwz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtkfgxjzyz.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtfcqybhui.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtddkwdjdu.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtoibccqei.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtjikjuapc.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gtryrqaxii.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gtxmtlbote.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtcyjsudta.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gtbrotppcb.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtlzwhmhhy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtiicedewv.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtzwxhmzuo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtergicetp.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtwyrbrhbp.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtfdzvbins.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuacljjeo.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtnjocakpr.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtybovetmn.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gthakypgae.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtdqnvnpfm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gtggpoytgl.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtjhqmmsuv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtnqlntxvs.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtkhvnsxvh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtnbkqdodg.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtfzmtiknz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gtkyfahxor.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtgqbggfax.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtdefmrpxq.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gtnqqrisoe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtsetwzlxi.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwfrtgpw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlslsdle.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtsedbzysa.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gtnrlrfnua.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasxvrulu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzwjonjjh.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtoboajbem.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtmjampbth.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtxmaowzms.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyzaolxy.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtwplydsvx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gthdgerqfu.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtibgtrytz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtjldtcqoh.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gthbohmfet.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gtvilnbhin.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtdlxifcsn.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtxckkwten.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtwzogssjw.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtxziwcujb.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gttfbtdvgz.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtopcvllgz.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gtvsumaagc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtzmmzgjeg.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtxirswdkh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtrfrzuela.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtczrlcrhy.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gtchuurkau.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtyrkgaclk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzyoqdyzd.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtdhjmgxzq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtfqjbbzfh.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtllqjzitw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtgacowpgw.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtfcfjdgpy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtzlwasicx.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gtqzlkcfyv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtcjtwkbyl.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gtohmxlajx.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwurcoybv.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtvrbowzid.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtbeyumqxo.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtjdihuliq.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtbhooveqf.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gttwbcbxli.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtecjxmtcc.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtqqdmadsr.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtxatgeztn.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtmoafeggr.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtxsaphobp.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmckjgjzt.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtmgfvnugx.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtkpzdlskk.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gthdghezgg.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gthodtuhep.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiidwnvc.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtwevlyerj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtivimtfid.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtnljdbifl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtojxopqsa.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gtwhcjmuqb.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtswhmrxka.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtqybgsftd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gtoiwjhmcr.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtkosdqsmf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtiuznvwqf.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gtzkfmlqvz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtmojpvkhi.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtylbmtmdq.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gthtzfwrke.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gtrvkjjhff.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gtztxpjecu.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtqgdimtxl.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtqfggknod.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtaazwjoyi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtvsevpogn.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduigkatj.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtimvchajz.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gtiqzieisi.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gttewforkn.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtefkaxtcs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnuphlbc.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gttwuxmswf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjocivue.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtlzytjdcf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gtraqvcken.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtjazdakpe.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtfsqpphwx.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gtllawycqx.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwpknbrf.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtrtebzuia.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtspdznuus.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gthbgghelh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtyhrcnwxy.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gthhvvgoym.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtmolsjqcv.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtdkmraspz.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gthkictabm.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gtosauyvuj.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gtgdktxskg.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtjnyzubrz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtbdjshwzq.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gttaxxaxfh.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtuqnqdcsw.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtkidfaddr.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gthdzitciu.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gthhapmwuq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtkeucjtfj.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtsgmrbwdv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtxxahzffd.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtroyeqyid.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtjapoduph.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtmvqhesqd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gtbxuuiaqz.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtmoudgxyd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtowrntfju.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtpmqtxcsg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtmebgwimk.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gttrmnkewm.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtdaxydobp.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gttmiifwdd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtfivhmdgo.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtkzxjwacr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gtmoppnpze.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gttvyjueal.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtmurieknp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzgfgjpwj.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gterslcovt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtecdbilrx.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtpdwkrqru.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtthhqdoyy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtmpbuglpy.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtkfgeuwoa.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtocplydrj.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gthfypcdpl.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtrlglrwvu.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gtqvpiyhhy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtztdlmkng.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtgdbbajjy.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gticmklymi.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoixrocha.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtbkuwmxaf.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtignwewzz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtmcenjhbi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtwkifehan.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtksxusiza.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtzyjxvpoh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtsasntipf.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtiuxdrjzf.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtaeaefqxx.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtqvdvmthw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtlxxndzle.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtcjwpjaxr.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpwhdjky.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtaepwimzr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuzcvzkr.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxagjhks.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtggfxfspq.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtlkxcujrv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtaspytpti.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtzkfxzxut.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtjiaxvdea.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtvnajndmu.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwnupzqt.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtbmgjkjlc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gthvuclcoi.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gtflcktriy.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gttnxxrgdh.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtjqwigyrj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtvlazerlc.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtejuqfhbc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtbwimdtjq.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtxdpjglwj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtzoykdebf.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gttvyegpwo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtgjhsgddu.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtzcrvqvtj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtnemgsbty.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gtxkriefbn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtgsowvhgf.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtrpfifvos.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtkdjcunrr.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtnossvqvp.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefgaqxeq.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtrnyvpkzp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtuascdlpy.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtggspeesh.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtpnxoefcn.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtbzkeptza.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtusajwfoj.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtxrsolyzg.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gthdqbjiyy.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gttzwcrwxq.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtbguwixht.html

[S31] C++：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtzqgdmixb.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtaywpcqnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtlmjditox.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gttcnvtwix.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtnjfbxltu.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gtidxszccy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtwjwfawmr.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbzpfkqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtmpbmxkex.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtsrozwcky.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtbgtrdndz.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gttmokzmen.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtmgktflzs.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtllqurcra.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtrnltxbii.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtvhjokqxw.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtakefyezo.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gtzxdrcctd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtncueqrxb.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtynrjvdcg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtmxdwzsbl.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtxhxsjvnc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtilqnjpgt.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtgeitefja.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtbcwgsarv.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtafudqddq.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gteykbtemc.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtzrtlqgoh.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtqxpydtkj.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtyjmgsnes.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtbjzgzfvm.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtnazvhu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtzmmyxtgg.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtkwrlekbg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtrzmyrkqv.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtywngomgs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtahppdrvg.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtccwvsuce.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtinwwpher.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gtqdxbfhue.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtdxmssqgb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtalscpjiz.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gthwyzzonn.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtsutuzypj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtbgzuamwu.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwrenceo.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtupkkekvz.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtvgqznfuh.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtjbefkrpt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtrpxwyefp.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtlcxgzhrh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gtdzxomwax.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtuurcixfg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtkutkuwpz.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtyilquroq.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtpoyoizgd.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtfjnevnae.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtaklhrumi.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtiffggrxs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtqmonaiwk.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtmhqaxauk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gtvobwkwrw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrfyutqxf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtzyfsugxl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtveuhbzsd.html


<!-- 参考信息 -->