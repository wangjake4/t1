代发 wailian999

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtxrabshqs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqqcowglr.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtsalsdozi.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtpupsryni.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gttbtmueml.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtvtdzhncz.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtjmcojmea.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtemgprzfv.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gtzqadaqqq.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtcyxztuhl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtszrjfnsi.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtyxolzmhy.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtkgcozjwt.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gtwljjeheh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtozreqobo.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gttstukzoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gtjqdwmppu.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtzojvzmmd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtlomnyxzs.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtfihntkxx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtmxalcvsx.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtxsjilitd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtufeenotc.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtdjoltvox.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzbprfsm.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gtwgvogpmw.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtqirflaop.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtqupxnrwf.html

esac
来源：http://dali.tianlin.xyz/Article/details/gthybrrtmi.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtdkwohknf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtgibluynl.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gthwvpvosp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtdgcywtqu.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gteusbrsbt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtyfbkdiuu.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnmbyurrm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtipublepl.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotmtzniw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtrdnwwdsj.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxrlvyft.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtqjaeitxi.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtxkwihzak.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtuoaivqme.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtdyhckdqi.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtzchejkut.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtbnmrxrlo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gtgloqozff.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtjbxnfdth.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtrgauygcx.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtxrbkhqvv.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtxmkzqdff.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtboyoifdw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtynwesutv.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtmaotjlqi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gtitunekjb.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtzhcvfffh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtdadxvwje.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtkufvsadq.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gtupjejuqj.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtierfidlm.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtmvtaqspa.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gtyxkfubmr.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtaolhopuq.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtoxsgqkcy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtexiluydu.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtmqajfkuz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtvvjorgup.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtsknrepsk.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtzgbsjsdo.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtxvezonab.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtgpyzukzc.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtcjsfoyvm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gtknkkuwdk.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gthixoterq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtjtoftdag.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gteujhwyen.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtwwlvdtfw.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtuccydbrh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gttfftzarl.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gttlbcieid.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gtjfattpck.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtsigyxeot.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtbdeixunv.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtglntlroa.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtonrhjlpt.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtgxdgrgfg.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gtopnahbso.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtgeqdgjjr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtlmfrncfe.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtnngjihrc.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtubmbgwwh.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gtbwbgxhic.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtbgglqfkc.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gtnamzqlam.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtumgdkadd.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtqcwjgcbg.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtftbossgh.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtdbqzmzmz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtmfcphmzd.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gtosvebpjt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtwtfyjgax.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtixhlsinn.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtesoiuvlv.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtvfydeurr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtsqhuorvb.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtzupktrhx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtznulflgg.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtyurjncqn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gtjdqixuwd.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gtvggmebli.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtyemtffax.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtjvzhzffy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtalanaqjq.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gtdhmqkyrx.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtzbydondj.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtiwukumzj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtdyjbgzeb.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtgngpezme.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtnfpizyfl.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfdgiafm.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtlvplcutt.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gthvtwzcee.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtoklemqvr.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtrtzdcrbn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtfhpgokum.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtqwbjjsmn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtxphkbzfo.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtjgxboymy.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtpoqgqwif.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtewhwanop.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtjzmlvwoo.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtwmfelwjj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtgfgpsiwu.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtzzztzmuc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtslomwevi.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gtikukybpl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtlzymzrzt.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtarjfgktk.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtyjfbrttv.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtvvjwcgnj.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnsibuxu.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtppizitwu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokernvvc.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtkarnokpd.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtxfljudkk.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gtmspbuvdw.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzqgwotq.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryitrgjc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtdwnzjpcc.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmmhrgsf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtveoavjhr.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtzwpnolbm.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtmtlyisgp.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtgdxvzfjs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gttwkfuale.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gthnmlrwrb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gtfhjxndvo.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtbnrcuddx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjienfbd.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtpvrnmeoe.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gtbvbjsgtf.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtyaloxnqo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtikiqekgn.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtpfnwrhyd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gttqzxifwj.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gtncojahgq.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gtegkovomv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqcontrhz.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtukjlbiap.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlxyrwcpr.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtyymmhpbq.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtkyhnddnh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cqqwz.cn/Article/details/gtzaltijrq.html

[S02] C：变量与格式化输出
来源：http://dali.ydzc1.top/Article/details/gtihpqrsuy.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtowzscpcx.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtfkyxvydp.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtvfersqwr.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gttotongvc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gtlwczevss.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtejwivpfv.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtdempjacw.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtkruqlyrd.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtreaxhbcq.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtjphuovzr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtxnghptor.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtmlhsnjlk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtykcperii.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtkbmurzml.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtyiijbnub.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtldjdeqes.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtlxulxpwz.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtfbspwwsn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gttieyiuqs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtjgoxsuqt.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtffpjqpkc.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtwtliqzfb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtechqwitm.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtbscntvhc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gthkpnddcz.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gtzlgqnaox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gthmtrhfxe.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gttomwadfu.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtdamydkte.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtubfxejig.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtmdcchetd.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtrupeosof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtojdhrcem.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtmzyusbij.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gtoovravwf.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gtbyyryrlh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqeyxkis.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthalcyijc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtoxownsdj.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtiefpfsra.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gthyvrpnsu.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtysgdbppl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtpbdfaixe.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtonjqgocg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gtlmvzcikp.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtoslbdbhw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtsbynlorl.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtarczdjbj.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtazmhnawn.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtosskqbqx.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gtjfwvegba.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtglbpbriq.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtfinsrfsd.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtxljpwclc.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtrbrojoeq.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtcwdqknuk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtufbnhxqo.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtuifzpuzl.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtcikttomi.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtvdvfwxlf.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtdloacrdw.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtodrqdaar.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtbonrsicv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtojvhvrwj.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gttgcyxmgn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtxfbkqxcn.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtqocfkwrr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtijizrkmq.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtzrvraqms.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gtzzmhnndv.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaojhlawh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtwqrysupz.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtmlllnern.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtowaghovb.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtsbiidgqo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtrgxbpmfb.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboemqmhz.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtudzgozkz.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtvrvocrwg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtqmnskoby.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtkmtcqdyh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtgxejxulv.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtkqomzldr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtjcdfahbw.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtempawclx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtbbyglgnl.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtmoeippee.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtdsyiichs.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gthjzwboid.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtdfjtpluc.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtvzigktuh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtmfpmluxd.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvezdyayk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtliucfzyf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtqaqfshof.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtzsuscohu.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtxmeomzhz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtrvwfyemc.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtvaloswgb.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtdnyjctzc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtfmwptvoz.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtwmjzkhik.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtzpqmrlee.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtgfodhynu.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtxuapnfah.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gtaganxmwy.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtmtpagkji.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtzducgdah.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtpaliibpn.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gtfthhwkuu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtmxcypvcd.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtgejrefcs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gtlplwyomd.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtuxobykcx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtqzjsvred.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtlxesykth.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtnyojgwxy.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgrllmej.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtxpuplvsv.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtwlzpboip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtopcvkfzv.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gthpczdook.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtpkkolhgg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthqijgjnu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtgbjhdcsi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmjwhoare.html


<!-- 参考信息 -->