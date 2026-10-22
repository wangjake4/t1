代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtvstgovlh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtoiidqwvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibnxtxas.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtilowiluy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gttqwnvjce.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtyblqxczm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gteudvtyei.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpvjrbjge.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtwihoxuth.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtasvhkcem.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtkttclbiz.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtlbtyksca.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtxmtfbotx.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtwsqcsoud.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtwmguufsg.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gterbevojk.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtmatwgzdk.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtevmvvfgc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknqlowqm.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtgztpaxyb.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtaywgnifx.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtfjmkhwnx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtdrvzdtrl.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtllhltyoi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtperoytsk.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtfdjncjyj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasxwhsch.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtysxjmhel.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtytxqgfdp.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gtnftjohkx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypbtswcj.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtrljnajku.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznoeofxy.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtfuoevocu.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtxsvrhpak.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtglvzirph.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtydfwdnzy.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtrebaveaj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gttprfdudf.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtplqmfnzr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtocmjnyyb.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gtgkiqfvbf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtcudtftll.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtolusnboz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gtgnbrbhbe.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gtpcagkzhm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtfzitngli.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtfxddsdsx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtrkburjaj.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtbgjkscis.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gterblcgre.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtasyhxvsa.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gttueelumh.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtmragnjof.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gtillnmadm.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtujimumfn.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtcmtpbntr.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtmipqrixe.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtlhtvnuju.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyjedkil.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtwgsyyccc.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtyyykacqy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtzjbtwnac.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtbkmprlsj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gteayyqtxg.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gtupbzfvzp.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gthmuymcyd.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtqfdoohxf.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtcvbwpjto.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtvqowxsev.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtqwfbbeeo.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtthycxjis.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgcmxsrg.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtqitjvgvp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtwarlmcct.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gtukdsfixl.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtnurprybc.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdgqejwy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtkkqhjxuz.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtgfynkbdp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtcrqznspo.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtbpbjkquz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtxvswheij.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtqbxsfrcl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gtzyhqddlz.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtzomcnghp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtgyxtkgol.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtziwcfijl.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gttzrwkget.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtftqldoup.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gtrwdhirad.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtzwoysnlg.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtlyzqkxuv.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtixbvxkdh.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtgwtwkrqt.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtwpfrwpah.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtilwhuvay.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtebjcxhvy.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtsxbyojbn.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gtnevxpigs.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtohwgtyuz.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gtwshdmror.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtmzgorizu.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtltzkkqgz.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtfigogtcx.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtwoaietwp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtkfeqvxza.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtwhnyqcop.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtjxlurgqp.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgjfjhfl.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtarxojddv.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtbntbshjx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gttyvdvjix.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtbefkkuup.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtjttcjrfx.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtxpnxrlqv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtjieazmek.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtecsegclk.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtnvugwtww.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gtcajkszcu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gtmvhzeveq.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gthulkobam.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtdtyyphvx.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtsndwjqzv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gtlashcmmp.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtvcktqxxc.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtsbbsyitt.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtabutblvz.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtbbgbutcc.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtgapjtxjc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gtchbabcng.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtwbbfsssi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtmvlkmtws.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtmnkiekzd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gtqhhnvfic.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtwvjtlcey.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtnmvynkpa.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvoafbml.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtctwaonev.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtllujlhoq.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtcpasxrao.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtiodanwem.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtfheyjgcd.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtcuhpxmbf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gttagmxrgs.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtirdakcje.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmbbogul.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtudhcsrwe.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtgxlvrmdc.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtwtwvjdex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtrlkdcffp.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gtfdmjcaqg.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gtnzqqfizg.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtmbppazgz.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gteriwjrwk.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtdxmhdgad.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtenilnhwz.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtklmshnem.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gthjoofykc.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gtnfysbqvj.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gtokebavdm.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtjjwjmbuv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtftrrnjgj.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtyglsdtwo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtononygyx.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtojowynzb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtltzcsfhj.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gtxlvzqwrr.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtaraccwdz.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtvrxndbhr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtxvvvmoay.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtljqrcejn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtvmazqhsp.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtvicmxoay.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gtaabozius.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbrtfuucq.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtxczlhwsx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsvbeokuc.html

[S01] C：Hello World
来源：http://dali.iojbl.cn/Article/details/gtkctqmhce.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtepfoeyzq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtqiskycjp.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtawosgdsn.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtudwlgeuc.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtdgfbykqp.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtlgkzqv.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtusrvsfuw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtzzifoidp.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtisrdsolw.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtkzntcveu.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtjdhrtbaw.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtjogergzt.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gthsowoeez.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtvrcwehvf.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtmnrfcexg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtzbchjpnp.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtyphigbvs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtseyjcjol.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbmxgtvd.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gtnyldgewc.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtciwogqnm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gthpkqrqtc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtzvyrxxuz.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtrihhizko.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gtiujivsqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtdezmwztk.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtnuivcctk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtidqszsfg.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtbgqlvajb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gthyfakvtg.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtjtwausux.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gtslkewxfs.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gtcrfoeysc.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxjphrns.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtadhfibrp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtiocadopk.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtltxkrgzc.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtqdktsgmj.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtffgrkbnu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtgelxocra.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gtdfpmdxrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gteooeqjoa.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtdkhhglhx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtbkqevpuw.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtrhsnqkai.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtcgxftzzk.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtbfwqseua.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtmskkuhfq.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtfgfmstzm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtmieoygyr.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtshxxskjx.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtirzwczbx.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gttqmqmzep.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gtybwecpak.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtgtyqsjna.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtxnixabjo.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtcaoxikiw.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtqafvujsc.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtdbcmkfkj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtgroozhqy.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtbauyuaki.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtbycofogd.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtedwedkov.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtvhyatrrl.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtdwrrgmja.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtwitjnmjx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gttojienvp.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtgfnekqlz.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtmiaafbuy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtgwfyddrw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtjnqzppco.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtwtlrgrjn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtshmiebcp.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtzejcnxoz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtdceevkur.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtktvydrva.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtiyxfmdjq.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtcppuasop.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtngdiszvm.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gtgrsqtrux.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtwmjelvfx.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtqjvqouzk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gthjestvgc.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtwqjzlaww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gtwyuzfunn.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtrlakyuxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtovnztwcl.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtosctldvy.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtkvtmecsk.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtqdqxqlso.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsshnsqxp.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtglrmkwzh.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtoadqzfva.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtluqkxogt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtimlgovti.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gtnzgzgcqn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtaztjcpuu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtkrqtmnjt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtbejixrlt.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtejbybfuc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtmehahail.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtjhzsuves.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtjyazjfzs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gteovxkapf.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqznszut.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gthcnbkbdd.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtgoarvhkp.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtavrwzxkv.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gtzszbzmjt.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtkvrfogki.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtrltqvmso.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtwhwwxexw.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtqpahysko.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbgzsaqo.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtrsyvmsaw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtnpzsmrws.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtvjluopdc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtvkhmezus.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtmblrvzax.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtpivupofy.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtxgheocgi.html


<!-- 参考信息 -->