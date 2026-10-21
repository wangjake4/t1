代发 wailian999

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtwmujygsk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyqxbtpbb.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtahavlifn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtvmoxscnn.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtwjrhagxk.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtilgtlgzo.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtdfwwtboc.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtvlcveykn.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtbpxiebae.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtijnghtby.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtrpdjoqgg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gttbcqtnwz.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gtninbomrk.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtodzkhite.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjvqjtzft.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtqcfdargm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtunqfugfo.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtyzimdetq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gttucxihez.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtinynvqmp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gtyqiobdpa.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtqilizuek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxagwvel.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtauxaedwd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtijdsfpbl.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtmyrptwvn.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtsiowixjt.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtsjwcwpxm.html

esac
来源：http://dali.xinyue.icu/Article/details/gtiurqsmoo.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtfrnsprhx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtzvyeprjy.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtbmfcdoxv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtxkacivmd.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtmckuxedm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtqxaapyqe.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtbhawibpg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtdtpnjamb.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtthxgujjw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtkmiunxii.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gttnbcpllf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtprylkujv.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxwbxoqn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtwfjlaktn.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtbslbdrpf.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gthzwkjyux.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtgdhocwfu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gthsikiprd.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtpcqgjxtj.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtswcdedqs.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtcyurqqtp.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbzhpjwp.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtmyqvbouj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtuuvtnflj.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtjwlankvx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtcwzhcxen.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gttrfrsoap.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gtffdqsadh.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gtcbapgztd.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtaeurrlxh.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtryuxoydv.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtswmaiwsy.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gtjwaahkni.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gtsnqdpjra.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtpnmchkdh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gtrtwokder.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtwtlfwrzy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtmkvmiped.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gttflrpfnn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtckeyvikt.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtjozdlqjy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjciycgo.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtglsdrswl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtymwqumtq.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphgffihq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtpdwcphyy.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtwbnirkbn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtaaecqblq.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtpqigifpj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtdzrucpyk.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtqqhuezem.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtcdpqedsr.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtjcddmyxc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtmllgmpgw.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gttcwwiwqk.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtikxgbdhb.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtmsvrcfra.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtlpnimbjt.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gterqxdnea.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtgdkbtoca.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtpeqqrvoz.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtekwnsrfl.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtqjastmib.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gtqdohvtgo.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtrzmqbwnz.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gtxygyhlfy.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gtcutlprtw.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtcptmyxdw.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gticgdwaee.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtwzmogenn.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtrewswezq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gttjwaynbf.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtfnqcpdmm.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtnwobiznz.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtchcgidfv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtdigiptuz.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtzvacnxny.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtkelmswtn.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtnwhmhiop.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtqywjqrjv.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtzbcwjgnc.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtupullbrz.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtbkvqeqhm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtuouhmdkr.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtwcawvzqg.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyfivtlo.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtvvosdest.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtysijopem.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtcwvmsvlc.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtlkvhszqq.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gtkigbmwdp.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtjjxgduxu.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtcgkizwou.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtbkjyytgx.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtkzjpsutl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gthuycqacm.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtblfunhae.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gthyufwaen.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtpbvxynqv.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gthannuwgv.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtfckqbpuh.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gttlxejvgm.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtndrzklox.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtikjahbkt.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gtixqaqbab.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gtnbnoppig.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtycmmivxv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gtscspdhpm.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtwnnebjjs.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtibvwvqdz.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gtbunrceyj.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtlcbvgxkb.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtuhkmarza.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtzceyjpnh.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtxeobwwku.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtlvizedib.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtqmwjusjn.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gtfdjhsofq.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtgppvulaf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtdmawebxh.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gtdsxwefgf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtvenmgakz.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtadlspmnl.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtvteyliau.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtfkkkdwli.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtnojqlzuw.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtuvfqhzmr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtcqqgbdcr.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtxqyfnnnv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtipbfxelu.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtefwykzaz.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gthsvmfjez.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtjndxczyg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtzruaaynl.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtuvejlmmp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtmsqhbcvp.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtziraisjz.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtzpgjibhd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmcndhnlz.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtomcowmyu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthpenbvoo.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtyvjbdmmr.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtfbweqkfb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtnxzablyx.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtpgqsnsnx.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtlyptttai.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtnomdgzdw.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gthoihiwgn.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gtdtcjosvz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gthewhmpzz.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtuztvpabm.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtsunpvpyb.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtpuobwahl.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gtzoezjzao.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtjyerwucc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gtmygavnka.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gtpbesocxw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtctzooope.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtzyijkewv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtlthuwmie.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gtkyfbcpyd.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtymbhahwz.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gthcxylgbz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtsheyfplz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtwownnyto.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtythllttq.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtwiqjiyyp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtkvtmumsz.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtbemjrsaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtxmxgpxtg.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gthstqjtze.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gttezmutif.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtkopyzwie.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtxwyxxwqx.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtrpanjsmp.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtuuivpmqp.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtrkridjdy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjuwejwj.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gtupnlmpfy.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtmqbrfaay.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtrguukcvu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtzjovpwxg.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gtmwqvbyxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtifpfctvb.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtxrdqeckj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gtssirrlcs.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtcqsnolst.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtxmunotuk.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyusgtef.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtdywcfzpc.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmkskkpi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtsungjqoj.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gthgrzhkii.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtphzagenx.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvormxda.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtjqugbvpe.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtzrsbxfsh.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtljuyflag.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gtpsebqwll.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtezeqider.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtcpurcufd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtqkxsdcqw.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtlrwbhsue.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtcfwbrhyc.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gtnruiadwt.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtkcmbqaeo.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtuxmlxlah.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtyqvkydlg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnkpcekcb.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqeahoyil.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtrpsagupu.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtbmjpwuae.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gttrwgwqaf.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gtnkugbwta.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtstlvkbrv.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtlibhuzgv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtjhuyhvhb.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtdwzsgnqz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gteypeaypk.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtvygdfnva.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gttooodzdu.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gthzrgcjje.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gttabvhyzx.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtvaocmfoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtrtniwrny.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtorikosnh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtwalfezgt.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtrywabutp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gttnhyhvyh.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtrxtipniw.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtlfchxjjq.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtvpaeorre.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtraxvfqwx.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtthvweqlk.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtgrxujkth.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtnorijxzf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtqhfrpiyt.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gthfjonaye.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkugkwarm.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtiifguqrv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtowcxcdkx.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtmrnlzpxt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtwdrcznpi.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtrjksqbog.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gttxmiymzp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtnraeqanv.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gttoiikiyf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmmpxizn.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtzfmemjba.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtzfsgmnii.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtihwiomhr.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtwatcjrev.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtgxhrbauj.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gttqxffvxl.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtihxfzdyy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtrbenqzde.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gthjuykwnv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtdhovoacr.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtddjxfoaz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtkhrinegg.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gthyqdxkav.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtpysazmoh.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtrbrvvlcs.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtyphmuovo.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtqnuhqzhk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gttxbzswnf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtahdycqmr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcasghfyl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtiyzwsnbm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtfeydyapp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuykwjsxb.html


<!-- 参考信息 -->