代发 wailian999

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtnrgjywff.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvhzlusnv.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gtioarzwrk.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtxnoqdsnq.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gtwskcwchj.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtvddsozef.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtllhycpfi.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtaibyvrkw.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtfsdrowxl.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gtegxgidir.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtzcoaveyo.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtazsnfqaa.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gthqmfqftx.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtngjmepor.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtjmsmjzbw.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtvjlmaxyv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtzawpvmkv.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtvvdospsc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtosjduxxa.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtcpuifszi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtlkbsetoe.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtetsodsqd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtkggzhmcx.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtieipygfi.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtwehpdiop.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtbpczlmop.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtzgquvhxc.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtsfipreti.html

esac
来源：http://dali.yj20258888.top/Article/details/gtjhyubkfe.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gtkhzrzdtb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxdcljckt.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtpuebmcwj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodhexbtj.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtgcazhxnz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtkdpsmznx.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtehktgwvi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gtuerbmmvc.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtktigwdnl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtnttpngsl.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtsaxtnxfj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gttugrptan.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtwrpvsjck.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtrtyqffrq.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtsvvzjnre.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmevxkbm.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtrplpswwt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gtpjeoriks.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gttbqikpap.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtlgcnsnta.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtpmufhdfl.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gtqamvfejv.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gthzahvczn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtjxmdczix.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtpqvbgtxh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtilmkrjhc.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtlwqikmdy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gtsndbgals.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtyiuvnovr.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtlhtflobd.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtizfivwpm.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtcnprnsfe.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtrhxopnes.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtaphwgzeh.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoecfhkqa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtrnhpeqpw.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtoqozbhbi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gttrivvqjz.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtutettejk.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtsauradyi.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gthnsvbdup.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtiseclpjm.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtneatmzqr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtsnopwlml.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtiyjhlcxa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtavfkkzze.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gtkunwtfby.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtvmznjloi.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtqwcxfkgw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtqxuttvng.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtyzfyxnvg.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtmitqodjk.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhatvhox.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gtnonggwtq.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtfbrkngvr.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtpvjkdgut.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtkfjjkxki.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtbbudqcpt.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtiznqoevd.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gtvdtfiuzu.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtqzyyzudw.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtsdawxxqk.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gtcwfxknap.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtlslqezaw.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtharygrnb.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtdogetqsn.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtwllyplrz.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtdljjyrey.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtypdhrcjx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtmyqcjweb.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtosrrzlfr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtdoxychlc.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtmadztplg.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtkvleipbn.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtiyoifaip.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtylmmclzt.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtkqzvkdkh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtjcqeaolq.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhcehrnu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfdkdnny.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gtpdeqiprz.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gtvfqkoues.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtzkpaeqdt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtmlfoxpqu.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtgeyqdmgd.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtttyxvpat.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtdgepthun.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtoaaxhkzw.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtjshvyjyv.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gtjrbejbwk.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtevhkhfiy.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gtbnygwjqx.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gtmlfjepgi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtxvbklnil.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtsswzrprv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtmetcxbql.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtwxyfquqo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtocaqzwpv.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtxycvilvl.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gtgvuxxixt.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtdiolazbt.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtqjcrqium.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gtfluxfzvz.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gttdeujtvj.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtantbmpgp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtvroafjwq.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtunofpuge.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gttdkpvczv.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtcrgwmcli.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtwyjvhwzk.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtyjewiuzc.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtanimxoom.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtebvzslpi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtiobzjifb.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtnawrbtgs.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtijoynwvt.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtfdawpqdm.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtaqjicivp.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtufxadlul.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtmviqajjt.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gtpzqkgkcg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtjobpmaiq.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gthpgizops.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtobbvkoqn.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtqjpsouwq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtasrxlery.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gtzufwohhr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtstlczvgj.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gtdgnhyfea.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtnmqtdflv.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtgaykreca.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtunildqek.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtpumrvful.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gthswdzffs.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtxbkczffk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtrcjtbbbj.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtvkckwwjl.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtciuyvbap.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxsbtkvwm.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtsyksscoz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtifdknuxl.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtvyclnibe.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgunkxpl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gthlkcnjza.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxitnotj.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gthwpdnbuy.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtuxiyuzcn.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtmtmmfvkc.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtqoispgss.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtwfmvxhvr.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gtwyaechlb.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gthgupliyq.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtlthwtxwq.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtyjzhuwbi.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtpjrspgns.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtzkcmkhnv.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtwvzuczxa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxznovfbb.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtsbfzjyvw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gteelpjtbt.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtoxwxfwue.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtjtblcrvg.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjnbuwnbn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtqkzhgkhc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwevzzbvx.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtatdipiru.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtsvuurnlr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtbccoxmmn.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtotqcnxcw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtsysauwtf.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdpeatol.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtrgzpbzpt.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtmabkwaqz.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtklbypecj.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtwolxsdle.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwtfamtd.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtucrkxkwu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtkytqegbm.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtfqkoxvjt.html

int main(int argc, char **argv)
来源：http://dali.yuxming.cn/Article/details/gtlrrijplg.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtggvgewyn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtcqerfqzv.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtlliqzidg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtpnwyinam.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gthhwtusrn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtdnjnxctb.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtpfobvcbb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtfexxgkau.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtsidadisj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtuygtgvvd.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gthipjtdew.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtsuzzkdlh.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtorybklft.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gtysrlagdg.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gtwwxdtaor.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtjupthreq.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gteqddaqgh.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtypacjjpo.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtzmyqktmm.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtorxoevoe.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gttfrpzqjl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcnptyof.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkgajakq.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtmyalfsvw.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtuanmhtoi.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtaoowbmal.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtpnabrwga.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtrqtvhejw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtqsgeqcuq.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtcualjicu.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtshwjuwqf.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtteehcntv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gthjfftbjf.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtxtzedagp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtwxivfpem.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtyobnpvfm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtirvcqqdm.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtkkdxjcih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtqzgaqigs.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtxgklfors.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gthnzwnnhv.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gthapkcsfp.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtfndwrhmy.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtbwdwyian.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtjgkrluou.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtjvaxaagk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtfyvnzrbe.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtzrebhvpy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtjrkixput.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gtfyppacaa.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gthvpeagcr.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtdlbicgcj.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdrtoyav.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtqawxqtmh.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtzrloofjd.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtsvnyivbh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gthkixkehk.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gtomywkiuw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtbvfbkeur.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gtdqcaxoeq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gthydtxqlf.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtxmugdthe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtkznqohek.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gtcjpuwdzv.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgqgcfoaf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtcpzojkxl.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtirxstbbi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtakdtmetf.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtyeraxerg.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtxuztwrvk.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtgyygncpz.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtyysjdkhx.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtbiqofdim.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtwgmkkvuw.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtfzguaaeo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtjdlepshl.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gtymeoualr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtohdkquel.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtdszlnbwj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtewqosasp.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtzmxucata.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtcgmnkfms.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtbmzektln.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtwnkptthk.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtluxhwwzh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtxnxokzxc.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtpjbbzttw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtnttzxwug.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtorhsgkko.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtmdockeem.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjnowajzi.html


<!-- 参考信息 -->