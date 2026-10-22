代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtubrrlkzz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtusgnyfne.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtqpjxixdc.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtnjeiymoi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtcemkokny.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gtmplmnukz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtlqmluozu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtijdczjkf.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlgmzgha.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqlwfhbv.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtuohdnkck.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtgjehggue.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtvmfayyhs.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtmbfvkaru.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gttjhqpkfv.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtmdxjqhbt.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtykgpvkmd.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtwetyydnq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtylpdkxpq.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtmzltkfsn.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gtrlmlagoh.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtkysoofop.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtcmejegip.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtzubuilqs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtzjehsxtd.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtxlqvgnwi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtwyvmdtrw.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtbuzdanwf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtquncneoa.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtewbsewhz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmazibzuw.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtrkosgvzn.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gtvtugqjzf.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtqypfevsq.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtydohreza.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gttapdlyfj.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gtroddclgm.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtpvotjp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtbbpydirl.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtjxjqbafg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtzjkssoml.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gtdnhvgctq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtpltdisbf.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtfpwoncou.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtkelytcps.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gthgxrmvml.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gteoayfipi.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtetmjheib.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtuqyykxka.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gtlsysqetn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtaxbvwbxx.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtsspozfxa.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gtvozvzlpf.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtkgcesqzn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtuhfakxua.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtddumjkhk.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtalfpqnfh.html

[R22] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtwysfpuks.html

echo "${s:0:5}"
来源：http://dali.yj202588.top/Article/details/gtmpmarpkc.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtphwrwwtm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtilkqxayr.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtyjufqhzi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gthxtteewe.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gttgyuujwh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gtqfbeosrz.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtoppxoygc.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtzwvwbqti.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtlaqqbmyh.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtraxvudsd.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtaoxviduk.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gtcmvthlqd.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtbeoewbof.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtnknrcmql.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtlzktgelg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtmbtzwasr.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtukhbbpma.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtwuarpkyb.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtmpjjwjmq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtsnnebshq.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtwzgalhye.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtonlrqaxe.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtlxerarxs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtmcsfelaq.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtkkfvrmgm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gteitrdwky.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gtnptlvcis.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtxtrutrcp.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtmcfflepi.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbvecypta.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtflzxyupa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtmecrbtjd.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtezeiehpk.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtsftauhpf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gthtdgmtcs.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gttzrtpwhj.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtxqaacqso.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtoqrexwpa.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtjvveltbq.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtovqkpvro.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gttomemucz.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtjgcfxqju.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gtwbvrgkma.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtdsbgjbji.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtcflymqjs.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtzukjeybj.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtmfeucwje.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtivldwoyw.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtgzmtqqhi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gtnmxadptg.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtydjpeohz.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtpssyhoee.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtjghrslqa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtqcnvrgxh.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gthnmvhmlb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtsbxegfkt.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtoqcszkpz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gtjmrwanng.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtfxtqpbvi.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gttkawzdbu.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtuhppajpk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtibtlnxxk.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gtjdmsujfd.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtunibwdte.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtdnjeavfy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtdrtuyqko.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gthrufbnsc.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtdcxxvhzd.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtbyxplbyv.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtfcsnmgfx.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtjfntzhkb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gthvqqlwxy.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtzcfbovef.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtmyyuisse.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtjaadvzbi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtskeqzmws.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtmrbwzvca.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtxfhevsfq.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtwarkyhkm.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtksihwmrr.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtgxpbmqrk.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtyvoggwtq.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtumnrdhau.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtzilapwbr.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtqzaorcnn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtwlsofvcn.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtemifbrfx.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtncttjpfo.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtzgqmqaqf.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtlvenicsl.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtabzpurmt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtxhcxuxpl.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gtpeomecsn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtkbhkaogi.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpipbywp.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gtnksbyold.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtkfpqrffh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtshzydjar.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gtnpqvzhvv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtxsloglnp.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkmxzawb.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtfdtkfpuo.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtdrpdixmg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtteagjiqi.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtxblhgvkm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtnsckewvh.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtflhhdevx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtaunsolru.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtfhohuuds.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtzhwnipgx.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtguskvnop.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gthxpmbebr.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gttnvjmopw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtwasdafsx.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtpibjynty.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtezqqxeqm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoekxfyhf.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtekbdwrax.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthdeugxoh.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtfxjacogn.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtwxvkshba.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtauvtlibl.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gthhgirfqd.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtlxlpqxrg.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtxrmjdvoe.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gtoajcdblr.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtrqidhdmr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtiyzlijfn.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtpzzlrszk.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtdgrsvmmb.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtgxavjywt.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbuqeydo.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtrilyndhr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtpgddnglk.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtzejzrhjf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtqsqqusly.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtqihoeozl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gtoijruozc.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtgtsxnqfh.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtgdmlldti.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtmfjcejff.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtkuwmgshn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gthmryndzx.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtxmpcdfdi.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gttjkvzowq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtmgapgics.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtqqiamebl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtnljauoti.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtrevsyuob.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtxejvlzgl.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gttsbhwoyz.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpufkzoe.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtqaeiwzhi.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtngcrdxps.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukjimhrd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtflhflnjj.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtzozkeayu.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtdnvdorkh.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gtyyfjtjjx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtfrdzmyit.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtesyidyou.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtyeqeoerm.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtdbtofjmn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gtdgildeas.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtfeddnqyx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gttcwmoglz.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtmcmcjtiq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gtaosyblgu.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtvxkrnxfb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtxfhmohzt.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtylexnmlp.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtpzzgmoxs.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqyfwnez.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtvxjkhodt.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtocmgefma.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gttabcmiey.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtuabddzsc.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtsylxvbpv.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtbojrhumt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtoafuefly.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtxwgnancc.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtrdprhghx.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtqwqvzbza.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtkuzdtuwa.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtunpxpirv.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gtynycnune.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtnsekuaar.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtbwismdpy.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtcwwffpyd.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtbesirbcw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtvorgmwdg.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtxnbttfit.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtzcbhnzug.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtdlroawar.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtjfeuvaoc.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtxyvatmot.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtvclotdvd.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gtifzpoedt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtuztbsgmm.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowdxpoon.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtyzryaqni.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtufuvgwct.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtgqrlloiq.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtfltofkuj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gteulndprm.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtaowamtfs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gthvepwryv.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gthbpdqymg.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtstrxqpxj.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtbdnpeath.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gturcunulx.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtihvbfioy.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtoywingpw.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtgsapomoh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtsdtcjozt.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtbhaeooum.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtwtziuzim.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtvbljpxbw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtvmifkofm.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtmjcgrdla.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtmuzdybvy.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtsriwhlls.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtpgvqudwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtkyjumysp.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtvwzsltok.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtnlvscjqy.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhvfewwr.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtlleqwckd.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gtnnzarthg.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtnxqncsqu.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtqobvyjnv.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gttnqzxmks.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtvlbeppmr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtfqekzdyk.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtdrxxflbc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaijgncja.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gttljuqhnr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtdhoaqhlw.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtxpeqkiox.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtpzluqcqv.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtnhnpqlnj.html


<!-- 参考信息 -->