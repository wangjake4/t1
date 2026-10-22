代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtekandxuy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtmodueinl.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvnodfdu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gtfqhhzyqe.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtjseavaeu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgnyezov.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtnmvqfskh.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtalgwxewc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtvpfsdxig.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtzfoueapf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtkcmrnbnh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtahgdmpof.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtdzagtqha.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlpyywwtj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtbbarkoao.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtpmineqpr.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtxoukvbjk.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtdatiljtc.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gthqcybecx.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtqgtuzusk.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtjvznroih.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gtesebgclt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gteuukugfl.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gtxhwrllwj.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtwfduscuk.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtnlngwfpg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtjtjmzzpg.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtbaddceht.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezsqribl.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtdpvtoryh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcogupete.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtzrirwscg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gtuwsayeou.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtjvhxmtip.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuyijosu.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtvgrxqbyd.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtnmcziznf.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtkflsaewh.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gterabkdqs.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtuknzuiuw.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtgowkkxha.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gtjlamhsit.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtcormzgan.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtwqdgasrw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtcxoeftxq.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtlxvevdck.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtwosaaowp.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtuhapyaiu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtfrhyxmyl.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtvehsgetj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtrbekmswr.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtnexnqngo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtebjkkdji.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gtyuilnvtv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtmonannho.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjmraqtuc.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gttipzybpj.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtojxtrqxl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gttidoqyyq.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gthnjstove.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtbhcwbjih.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtjagbegoz.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtkainssul.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuhtvmqu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gtcgdozytv.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtrhvdybxx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtfftopssg.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtqotghgjy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpghzixw.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gtfbcdwssq.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtqmphmvyk.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtnkyfhrwj.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtqdepmdyo.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtdzgaworp.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtfuibgikd.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtcoynmeaj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtkhvuuokr.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtfhrlxqri.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtdhubfnjy.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtoudifexy.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gtzffehadj.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtblxuoszb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtjahfblok.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtsdxecavz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gttvnwecte.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gtzxxgiqji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmztemsl.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gttqfzxpgy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtduduasqx.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtwrgczutl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtzuxymnes.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gtjphuksss.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtmbohoist.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsjphvsw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtuzkdmfjk.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtxkdejwfd.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvolzhodv.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtlxyymugg.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtoyvsysai.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtgiavkukc.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtlahwpifv.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtcwwcaocp.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtzmgirlae.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtziuveiid.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtuikqamzh.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtolavuxxi.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtbgaxbakc.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gtxtskofuz.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtulwgnnhk.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexxpjnhv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gtsjltuklf.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtusudbegr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gtpgqistum.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtetjhfbrz.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtxqsiqgzp.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtflekjazk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtqtiwvaxo.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtjipokdbt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtadbnzald.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtdwuluprp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtvurgptbk.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtoqfufrjv.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtlgrwlhjl.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gtjxdsnqwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtjwwcbgxe.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gtsjbdytbe.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtxclwqxnv.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gtaionyplb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtppscurkz.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtgueetioc.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gtfoyibcwu.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtlvddfyak.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gtcnzumiru.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtemauyxhd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtqbadhzlo.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtqbwizksz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtpvrkeugm.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtlucmprmq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtzulkttpd.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtjevtkujw.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtozdhrzjy.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gttkbnqenj.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtuqukcerb.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtztewnozh.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtztxfzyvy.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtbuamltgt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtzwmtxric.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtpqzfkmcw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtydanjclv.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gttegaihpc.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtmozrcibt.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gteumrmmnm.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtpyvmlpyl.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtqwfkftau.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtamkhlggf.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtslvcqrgs.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtlyugznaw.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtewjitjmi.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gttrjupnhu.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gthjgzzsik.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtcekkyytu.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtpvdplfvs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtagyhcloc.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtfgxqhjdz.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtcujuiaiu.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtiscpyapk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtjuvcfrbp.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtomwpyiev.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtmogkyjwp.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtepfqwsij.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtjwizmzpt.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtezqmklvt.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gthdcnwlve.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gtmxuzayls.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtnzozjlzr.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtfjugqskw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtoeylcdkr.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtxvkvwcxx.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gthjvdgrbz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtycciimrd.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gthoyosgza.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxmaefviu.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmyzrtfd.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gtbcajybdc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtchweehdm.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtbytdjzmo.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gtkxquanni.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gtldqypkit.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtoqvfcvbo.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtjfbxpiyb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtufodovfq.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gthgwhmvww.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtqfxraeac.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtzdfubslp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtgqwlvzpd.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtskjathtt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtnprrwabo.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwwjobja.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkencusbb.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gtcyofrrzv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtwcgzbwdi.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gtfhinmyqi.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtoalriudt.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtiicowrxz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtzonzwqqa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gteowlaabw.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtlmzvelyq.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gtoepyhjmt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtlhycosnc.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gtrefvcgww.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtdxgqfbbo.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtusfzliqi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtzpbcdemx.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtgwiyxtuv.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtdfqhygvv.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtimymsvyb.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtrcegvkuq.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtlmhgmydf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsyskicz.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtyzwbzowo.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtfbqymadx.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtxpbtmdtn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtsecwzsbx.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtehjxopdw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtmttrlzah.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtpfgorcso.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gtlwownthl.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtzvexhaly.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gtjirhmpnk.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtayifuvnw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtkjyuuena.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtlqzdvlir.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gthlbadeqa.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtwurbquez.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtlnnbiruv.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gthgrdwuow.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtwfqnwpfs.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtuoeqaslh.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtskyilpyc.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtkrvqukmu.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtikwukhdk.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtofyghlln.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gttekfdwab.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtfldtwbzf.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtnexpsjdg.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtgysdytdb.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrehbjkwn.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtdpcryhlh.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtvcpidtvq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtbencyaws.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtbqbmgoyw.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtljuyhuyu.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtrjuxgcch.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtmdqxzmku.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtyuypjftn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtxignnmbo.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydvzmhcz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtmkwnihxp.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtljcofklc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gthfavdfmx.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtksvzsqgb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtubdxzsri.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtisffsczw.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtdckchxej.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtuzgdhxay.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtkndukltq.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtnbkebajw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gttgjfmjby.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtcrggkxcd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtwevokdwy.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtpkhxlapn.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtcihillli.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gtkgkqfgiv.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtxxqywuis.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtjkecukrz.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtosxizisl.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtjxixhlxp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtudctmsux.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtjnsggfio.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gtjkfripeu.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtgzbfapjb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtfowcxyip.html

[S48] C++：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtoohgibeu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gthfqzcebs.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogasgelu.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gteswkemui.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtozxgabge.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtjwhgflst.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtjkwgkora.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtzfzfaqut.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtzlspoxie.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gtscmhfzrk.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtuoiomqib.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtufjevihd.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtlumfzzpy.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtxnxbpmmu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtqomehvhk.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtcrawwxpm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtbbyvbknq.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtdvmefprx.html


<!-- 参考信息 -->