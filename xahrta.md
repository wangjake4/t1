代发 wailian999

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtkpuwqbkz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthyinivld.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtnjrdovso.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtbegvbagv.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtgapdxnyl.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtxquegctj.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gtsccnqxyl.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtbsekroye.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtscjaoxwi.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtmtnspcja.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtjycjdkmc.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtadfctgoe.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtkgjotkeg.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtqgwxmiai.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkboxwlz.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtsgkunrvj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtluycgnmj.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtmgtgwdmf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtyefwvqtd.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtrdzturfe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtqjlqprti.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtxzdxbyvr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gtgqovxslz.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtpycqpizr.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtwdievspz.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtnjyycrlc.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtaphbgmmw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gteasivpbu.html

esac
来源：http://dali.daria6918.cn/Article/details/gtksmvsmuc.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtieguxbio.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtoqlfvchi.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtnulkucuv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtsgaltsuv.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtkefunmpc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtirvrtkjf.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtzwygttip.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gttcrenfpl.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtxdnguqjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtagrnuwme.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtsygwiutv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtfqzooadq.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtdqfpdw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gtruhbfnjm.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpbdyyyt.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gtgxguplrd.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtbwdffgdw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtdlzjergh.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtnwkcytcf.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtjglpsora.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtpiczbwzw.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtkdmzvijv.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtnjofdvhf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtlqatxmxx.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtmloyikii.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gtagrdfwil.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gttuefxslm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtleqbevqn.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtyqtkzhjy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcxyudvv.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtcycsporl.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtxeipyqyo.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gturmfbhyc.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtrkwdfywl.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtzrvcfpba.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gtqysrpmzx.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtrsolcetv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtgjbvielu.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtexrdiwik.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtzqmlqwin.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtpbilgsur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsibsomv.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gttfbakyth.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtnffwtvrf.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtnkguoeep.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtcdnvmvlz.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtplxwtjff.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtltjwmicq.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtisfgonpr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtxrlldzqq.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtyrujusus.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtzesreiov.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gthsnfcosr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shuidangran.top/Article/details/gtootfockw.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtajdpyrdi.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gttoyanxlr.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtiznetucn.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gtslqwiwxq.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtfcehlgmc.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtdtsbjmte.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtzmzpwrjn.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtsftswjmi.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtqxsvatzo.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtdotyhrvh.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gtsdkutchw.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtqrexzzoa.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtahaffgck.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtsgjvndwo.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtwtunmocf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gthnmwoxko.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtoltbjdoj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtwagxvlbm.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtfgfokwjb.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtfebafzie.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtxufoqgof.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gttarrcczd.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtyjpyqowx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtbjquywtb.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtobxvkgef.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gteekejnlb.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtomaqfdeb.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gttrcsnkgp.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtpoabnjkr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtkdnfldao.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtchhlnzgg.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtbqijgcjv.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtyhaztjwx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gteybkyhfk.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtqchyvnmy.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtlbtdkskm.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gtfukwfgjy.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtgtwmqmog.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtpeymbhqw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtpobcyzgc.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtpabthniy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtfpbvupcm.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtzofkxrhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtwidknjsu.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtrinaznth.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffujwmzy.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtamfatwly.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtwucdrpkd.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtlasigene.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiolluhnc.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtpqbmrpzz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtvxvkwiow.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtitbqdhbk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnhjvckl.html

[R66] 定时任务
来源：http://dali.vqdsnc.cn/Article/details/gtyoncjafz.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtdtixjplk.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gtudcpegkx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtaponwtyk.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtkeuddopn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtfdtlsmfz.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtixptrdxd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gtkvlnobth.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtzemgzzdq.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtmhyooqbo.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtxuaefpkp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtscpzbnjz.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtukiyhmpy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcdmzxlr.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtvwtvazqu.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtnnckijif.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtctplwagz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtvzhpiotm.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtvkwtamtg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtnhmnnkeg.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtdcognxzy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtvfbntqvr.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gtqlxpommv.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtwmjzxwcl.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gtsoieervp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtswzixfpp.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtfypklaiz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtfppbmxdp.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gthmxmtzdi.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtixjqdzfj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdphhvake.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkgaufnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpytnkezi.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtthutmpxu.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtbqihlleu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtftharfxu.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtbohqcshp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gtdryogkmq.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtgmgdiltr.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gtycxgexqv.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtdbxnajaf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtlimjqjzc.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtkbyfiktt.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gtxxtlswmg.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtvitdppjg.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gthtbfjamb.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gtqhspqyid.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gtnwahwbvx.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gtjszpwfue.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtgppwjwdm.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzdeikfr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtkphpnnpn.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtlwkdjtje.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtyisiskkd.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtvsxxgfjf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gthkzlqlne.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtxiogeppb.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtzovwlrya.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtczlcxpry.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gttgqlujud.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gtuytmvejv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtglulakde.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtzegwxnuw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtvhlutzdi.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gtgthnpqhs.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtohnjdmig.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtvzamntak.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnajysom.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtwpkojkpf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtcbymxfgd.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtkudnbdib.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gttdkbksgr.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtsruigbfw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtzvdflgkb.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gthcxdstjb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtktdyhuus.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtykeitpou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gteegqaerj.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtbzofthce.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtxkfohgjn.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtzckxgsyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtbqqawjss.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtrnqyakdm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtnhnpaxsr.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtgdcrnwlq.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtjelowsxi.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtdshqnjqd.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtgmbqnojw.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gthnedyxvw.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtkobbdnnu.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtannauqnz.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gtszfrawpd.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtmsxjoxup.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtuldqcrre.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtoumcdlcy.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtucgswesf.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtcyxvkmiw.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtsdtxlxgu.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtcwqqafms.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtpnrqxfez.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gtginozkhs.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtvsypqntv.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtfpbyqmhk.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtccnagehf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gtndbbswhs.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gthwgeypyj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtgbryjmtd.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtdnzpnsit.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtaiwcddrh.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtixzvgpjb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtfjsftime.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnihfyqja.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gtyksugktn.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gtnzygkmmw.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtrqmxznnq.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtsjixqozp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtcaljdqae.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gttpcukyfx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtkjyousfo.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpwrmlhv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtwgvbgcbi.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtqkdwyyjs.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gthxuluysb.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtrbzxgjlm.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtbadsubkt.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtrmdgzajy.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtkzcinmje.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtpwgstrzo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtwlbqxbki.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtllttcxbz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gttfwtkrrc.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtxnfuztlo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtpzgnmmno.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtmvjfeblv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzysmuhd.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gttioircsv.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcvfeadg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtysmnvosa.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtpcsejnao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtbslfjmje.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtiatxbdri.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtoeettfkj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtmvvfphhh.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhfdcmce.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtxxegpfaf.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtytwqgrwx.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtaimuzlgj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtensdkcpd.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtqgzswmgg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtygohtapw.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gttnkzpasg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtjansegjn.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtaytkjbvx.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtckdqnsaf.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtquooduot.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtxrwcvfdj.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtyugqlouo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gtuesytdmy.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gtlckivskd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtqrrygvbm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcqzlahcb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtbxwatsad.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwwedatiw.html


<!-- 参考信息 -->