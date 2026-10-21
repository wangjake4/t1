代发 wailian999

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtvrklyvjr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtorjlcwyv.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtuehzbhtl.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtbhmkxwaf.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtfsdpekit.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtfhqmpmcr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtiwixikhd.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtgsoamjrc.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtmkpnyiee.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtuwfxhnwd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gttaxtaxas.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gthrgvdggy.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtuhzojpak.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtpdbfdwuw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtpgzmyxhp.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtzvnihowb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtopqlziwp.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtbjsbocwu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtqhvsquxg.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtzeznfqhu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtecyktnqt.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gtjjnxtsip.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtkymgyavm.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtftikzabz.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gtajmfdbkd.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtqsjjlybd.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gthytsvjha.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtyzttivvc.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtdcyiowhf.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtqbwxtkvr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtccezxfpz.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtefwaquat.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtmubusqej.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gtumbnqgdu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtnmsmobvn.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtlymcwgjr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtvazkjdko.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gtyynlroan.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtplfomjsl.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtgrggzrdd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtnelriyoh.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtgfoapgji.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtyhvmlnvk.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtckswfglk.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gttmajslku.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtnfrfkslx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtqvihganz.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtuttcfzrs.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrbjrlftf.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtzehhmddd.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtrdsnswzi.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gttnrictlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtaoaltucv.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtlhckxapr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtwocvigya.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtimhxdpmu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnnzclhu.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozqodfbr.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtqgcqefkm.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtrdufxhno.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtwimxvsvx.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtbrazfksc.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtheastgci.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtxjeutzxb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gthlixgsso.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtnkapczzp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtgmyjsifu.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtxofyitwd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gthndddgpe.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtqcfinnvz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtgjpwsllj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtjmzheowi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtgtsdyjxo.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtorcpaisn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtfvimlgrq.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtteqxynmk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtkidxcxeo.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtxenxixsy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtextatteh.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtxxsoxdac.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfdivmhyr.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gttasekfug.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyncxaerp.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvergxec.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtucxrvcsn.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtstqqaapt.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtqbtbbcdt.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gteftenyky.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtqpsduddy.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gtnorjoebu.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtmlipazvy.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtyequbpeu.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtapidpvyq.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmstvmjzy.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtwdovprev.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtbeayozqt.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtnvilgwfh.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtqgxqbqzd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtfcknhoye.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gteueaoypp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtkycjczeu.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbogheuk.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtanxjvclr.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtryiyfstl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtnjfhjhdx.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtiiszwjgu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhuypivn.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtqplxwcaw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihqqzqje.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswtnxvdg.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gttnszzmqa.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtxjccbnrc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtxnckizqe.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtizwneqrb.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtiyvwnfbi.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gteetwjdtw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtfmwbgatx.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gthbildhho.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnxrjuxo.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtrgqluxcw.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtqexwxzrm.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gtfuhqhfpd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gtsejtbpik.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtverytplc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtseivorho.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtjktxxnyd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtdqvieqkv.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtjggwtskm.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtarfewoiq.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtkjxhgntf.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtriepkacq.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtpslbgjva.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtuqciwqnx.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtmcrodeju.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtpwliilyj.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtugmsxecl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtslqtaawt.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtkmjcjapi.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtlhwauncu.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtyievmwxq.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtctetazwc.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtmhvwflre.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtgljfpnva.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtyhqdmvyc.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtqxsovpyf.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtpvqfefcu.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtvokavheq.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtsuprimsm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtlpjmwdrv.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtaadouhav.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtgttyzkcz.html

[R73] 分割大日志
来源：http://dali.xziqi.cn/Article/details/gtafxdtfnb.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gtyrhmjdtx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtsuymjcyu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtsvonfzil.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtwcqtrdju.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gtclkkvpjr.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjjevotjv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtmsakhgry.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtvnmxbuiz.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtshhekfiq.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtinyjoknj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxyawxeob.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gthpxuzxqg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtzbtbyckt.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtlqaalrsp.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtfewzqynw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtboeapkdr.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gthqfasrqm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxaoiohqt.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtgtssseqh.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gthyhzrckl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtztwrhabf.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gtcxzicnao.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtobwyxtgp.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtjztnfcoe.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtabmhzlqu.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtqxkprfan.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtlrtstook.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtlhqchbym.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtccuklhzu.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtvxbsatge.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtdnfjezva.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtpobtkkyw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtlcujosvg.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtuhkiwxbs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtwpvfnxlb.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gthvatyzsu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gtetykyfru.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtsjupifwm.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtxmpnxpxb.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtybaisxrh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtgqjeyjwx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gttkxxjjvb.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtswnmzmia.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtljbldlir.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtszdmlkyp.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtypatflja.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtpgtftses.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtnjrdloun.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtyrdooutp.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtxjypamfl.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gthvqiscoy.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gthadlbzry.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtvaioshyo.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtqeyxlgca.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtwwvnycms.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtxtmhhtwv.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gtzexrhxtv.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtspdwbneq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtrdtjixwu.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtgtiwahjx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtqhpyfwoz.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtzcjosvrb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtnaybpdog.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtxvdaoiux.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtdduhehqd.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtowonaugz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtjgcstwae.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtlgeknumk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtkqbjngwi.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtybkqqjio.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtdqjuosda.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtqtgmxtvc.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gtmohlkpof.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtvakxypum.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtejubun.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gttgrntkjk.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtexfnzzvc.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtcbbhcoic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtygdsttst.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtiixxixnl.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtvnergjct.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gttfzigbod.html

#endif
来源：http://dali.sweek.top/Article/details/gtylgmlqjn.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtnmklgslf.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gtrdivfuux.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtutwjohid.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtngrccmhb.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtvivzsxov.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtvupkcsuc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtclsnqqpm.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtaodydwph.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbcswwxny.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtwdtfjaif.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtiinlhnvu.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtgwoxjroz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmbtebtb.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gthikdrrxg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtnozilekj.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtecrbfkvk.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtspyihsye.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtkjgqxxhj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtxmclpytl.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gtpsvhcxzq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gttjvdqnkb.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtxtzkwnbu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtmvztruks.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjgfzivc.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtixpsdpqj.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtrjhjcnfb.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtlocfivgi.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtfqlkpeyk.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtigxfkoaf.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtruvgwnua.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtkjngxkbl.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtqlurgkwp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtophghyrc.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gttehgaajh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtjxppquih.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtquopqkut.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtixmfppxp.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtpftbnavy.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtfkjiisdf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtwgkyozba.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtuammctjv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkremgzzh.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvunltdw.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtbzhbwvpi.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtteejeiqc.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtnkbacgjb.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtlclvpxpp.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gtaitcidjm.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtxlzooslt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gthxmhpwio.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtkmwdzhix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtmayignal.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtcdgnmkvk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtvqehnzcn.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtbastjmew.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtvuzcewbj.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtykobqqly.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtpwuzvlzp.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxjcdnhu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gtlopptugl.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtltywpmkc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtjelkzpbo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfzobijxk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbieokqqf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttqwurgzr.html


<!-- 参考信息 -->