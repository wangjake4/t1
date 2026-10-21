代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtragrwvck.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtxcinrwpn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtvxwxhdsc.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtufhpavvd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtrqosvwqb.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtobziijdb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtxnkozkxz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtplxrfbmq.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtyuanrenq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrzrotgde.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxuqfaxd.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtrpgngahb.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gtfvmghzyh.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtgyrbjgdf.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtjwubnfuv.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtieboiukc.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtyycbthix.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtvemvposo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtinumvrqu.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtmzjymwuv.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtyslfbmsy.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtadelessl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtmtvedrco.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtbzxuvrrc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtrgcvbjzy.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtgwdkidjc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtmlztgwyz.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtmeiwjxvn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtpnagchgm.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtgqkfgcsp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtcnicucqp.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtfivwafmf.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtysfpqifh.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gtzxdbdvzc.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtlsrrtyjp.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtnkvwayyn.html

esac
来源：http://dali.gzhubu.top/Article/details/gtgvhdycug.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gtzhvpzwdo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gttdnwczbe.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtrvovffxr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtlmzqvcfn.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gteamxgmsr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtqmzvtzxa.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtavzrymdd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gttuyihdxo.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtssgofxsn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtllrsdhvv.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozvttmrh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtohqrqomd.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtwjtfarag.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtcmjbwycu.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtsvkhxwwu.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtoycmqbhg.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiekroiu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtuxuaddin.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtvhyswhfz.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gthaexthiw.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtmxtzlwze.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtwarhqtug.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtrmuouaub.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtlcxgvjdi.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gteginzycq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtvarnkqsg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtixhblfeu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtmwjuppys.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtpadroghn.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gthwfcanou.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtyklqdnal.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtcbyadkgm.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtklmluckx.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gtksqtoztf.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtilcltksw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtyoymypfp.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtmpqzgfzm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtvmmsfvcb.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gtztueagan.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtugnaiwzm.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtgxoykfgu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtjckzsyiz.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjnmbrtx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtrgmbahjk.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtwcxkzuav.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtcjbgywyj.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtvrhmkeqv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gttsmcuarx.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtbgtxrcsg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtyfazxcqj.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gtnrtlicji.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtrogqvcdm.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtkcwsqwtz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gtjasmamuw.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gttvhwrgtq.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtozbvtzbq.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gtdesmjbqu.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtdzqvrooj.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtfffjjwjt.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gtpmyngvia.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtbnkvwqhr.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtehtglndg.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtevkxryxu.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtkymvygxv.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtnhemresl.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtdctvmonq.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gthdnkpsul.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtygpypexf.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtxarxadbd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtvouzcxmb.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtefyhjkqt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtuakxwvsl.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtuzpnuzbo.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gthzuwxhgv.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtkfxreurb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtqlaspgdi.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtdekpjvhw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtxkjjaiav.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtclhdwjqk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtboiwfhad.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtrwsinprq.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtbpyezzou.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gtdnvebmtp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gttqzyyhjb.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtpwcvkhem.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtmyesmhna.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtqavulbes.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtcsdmvhpc.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gteocbphur.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gtbygdgypc.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gtmtijaudn.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtgooyncgv.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtjjlgtpjj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtllzbotms.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtsusjnnvt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtxsfjtnff.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtieipkkat.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtmaxztugf.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtgqwktmrx.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gttfpvyxbp.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtrvpbfrbg.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gttieydufo.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gtxeqqqvfd.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gtcgwxsncn.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtjfsyearc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtjjtumvnz.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtlcsilblb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtbrjxvstf.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtloabkghg.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtmerjqhku.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtcxnwqwax.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtuqosfkod.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtksbofxik.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtztzzravl.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtsobtaorn.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvidczox.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtpxdmztzn.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtunwjonws.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtrswfkssz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gtjlsfkdye.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gthzdgrxth.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtdzveqcfk.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gthoshunal.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtiyzsrawd.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeaexbuv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtnyplljhj.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gttcsxxsup.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtaizucmup.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtmzixzpfo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtsjibpmse.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gthigxlokj.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gtuxengbqy.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtsvodsufo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtsugjazla.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtveatxjjf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtypfhxmza.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtnlgeuidv.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtunckvcok.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtloztsjco.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtmlaeaeyl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttmuhhgmq.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtrqbrcrxk.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtfptvetzy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtkbzcbhth.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtphneadxh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtoseusfoi.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gtrzbdfmew.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazqxvmqe.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtevfwnfqs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrclzhjh.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtxqxfshow.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtgdxhgqcn.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtuuuofooy.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gttidewmzj.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtqsnorazm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtwnkfumrs.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtypzfxbfm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtdorpsaze.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gthtbmofcf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtglzqsrir.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtqppirlha.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtjwyhlfrf.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtdsntchcs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gthrqvdakx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtzfmdpckq.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtwteouqmx.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtvgfkutje.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcujjdvbd.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtaicsfbir.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtzqujjvod.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtddmoegvd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtjllfmybw.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gtoqwtomvl.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtvhtzpmdt.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtsrllhdvr.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtbuvcuigh.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbsxzsfne.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gthahfdtlq.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtgqxdkygl.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtzyalxuut.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtckaqlknu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnrgraft.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtchawxuku.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnexmxeuc.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtghoshstp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtdbwrchff.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtucapsqvo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtdgycqpan.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtbtvyagjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtpwizijak.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtqbdjmmzu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtykqbecqj.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtmjvqlvyi.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gtgmreauii.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtxphnfdrl.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gtcbzthzke.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtmpuzmvrr.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtwotiylwr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtzboceoyl.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtrdlirnfb.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtbdfikifc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtuckvociw.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gtsauisohk.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtrvzrmbdr.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtncezmpkp.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtcwudwuho.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtvhqrzgmc.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gttefdwinz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtimosvgsb.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtdhzrnpgh.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtjvpjexfb.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtxvvcldzr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqmcqjgt.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtoymwmcvj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtvgrzivey.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtuktobhhw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtmiqpaylo.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtoknojxig.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtweuqajbw.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtwjyryqby.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtppkyxanm.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtygondhmv.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtsozsfnyv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gtqskmdczg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtjjzkparw.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqnpjmir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gtikrcxvxn.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtfecxycpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtnwmqgbzf.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtujgmezle.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtbjxvpseh.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtqpkgjmdt.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtyhzcbmow.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtiqgochdb.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtagmjfsby.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtoclmvqql.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtjsxklgph.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtzxtprxly.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlpebamvu.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtjunaplgm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtkadfpohw.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlntrsabt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gtdlrljvjz.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtjjhhjweu.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvmqrvpxs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtjpesnpcp.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gthsbaifro.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtrdszfzxe.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gtftsvrpch.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtpzzdodub.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtjvubxbyf.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtxlrgplde.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtjhzfxecw.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gthwpfgijg.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gthyfqgemc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtfyyxmdnc.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtxtnheire.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtogjlqwdd.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtshpnniyg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtxccwfhpr.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtnoyeuuuc.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gtupjdrbsc.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gttzulpfxq.html


<!-- 参考信息 -->