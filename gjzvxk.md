代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gtzzgspjjz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtbfebijbj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtettsrtfr.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtjpzahsgy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gttcupcwgc.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtnlvnbvdc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gtpnpblxyp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzfmvieuj.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtpxzicten.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtftyejdor.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtomsmyybk.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhciuzsr.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gtrtpfouew.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtutozebas.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtwlfrgisw.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gtnjawrzrj.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtybiiweqi.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixchttge.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtfgywgmli.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtuemslhij.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gtjuuzmjbc.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gthnsjwnty.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtkqirreak.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtttcmuqix.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gtsobrajda.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtufhgseby.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtfakfjrtp.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtxmyaokrq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gtodslqnfc.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtxvhoqsqr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxsbzbbo.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtvonlnisw.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtkydxxuhr.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtdxkgqbug.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gthaspnofi.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsmpwwwf.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtrdyvlkpu.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtqnugkbox.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gteofydynz.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtmmycahut.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtgkosaffb.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtnfynledr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtlqggpfsu.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtuumnyxlb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtbsjehaog.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtrzlqouac.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtujkvuses.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gticamkgjp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtdnpmheqr.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtjekmeqvf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtdvppoomv.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrugycjt.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtxyynzxro.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtgxsdldqx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtzuewffcq.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtmrlhqrzk.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gtneffvhuj.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gttjnlfmay.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gtmymituie.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtirbgntkz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gteufonvod.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtdrgqmpmr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtcjrqseam.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtmbfxxtbv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtdxhtrnki.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtyhfmbqfl.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtbpiwtbdr.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtyowtjynt.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtbeqbvehe.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtnxjdpove.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtrlkalysi.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyufognwq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtdzwgwoed.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gteeaaoupj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtrcrngmhv.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gttlggqmws.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtfmbwxjxm.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtlaokmkmo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtadjpruhj.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtkvwylgmw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gttfqmxtmy.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtshrbzqzs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtycffbjaj.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtlewdxvft.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gttikempif.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtyooytsrg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtokxcffpb.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtlhkeaevt.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtiglyjlgy.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gthqmxzzxg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtrhiirkxm.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtguywedzx.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gtgzhlvvpz.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtmlbqzmko.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtwvangqvy.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtweucysni.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtdsvmjqci.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtaebrmhdo.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtkrndofwz.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzblkuwbe.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtkpsbeaeb.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubjwhzli.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtijuawcsr.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtndvjdoij.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gtwtkumxxn.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtzedcfpfh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtxjhblfws.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtyjkyzsjl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gttxxnpitt.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtbynvdnsj.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtoieyybxy.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtwbsqmlvx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtbmyyrvei.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtcukkxnxp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtbdstrxsn.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtbqijaxvh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtdvmpnltt.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtyvuxkdzm.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtorlxopii.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxwtuoeb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtkwlfsgtj.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqhsfohjm.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtsxedicqs.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtvgftcrgs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtedthmtct.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtwfczrwao.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtcvxocywj.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtxkyxwbba.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtabkkzbqb.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtlbvnknsn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwhftxlm.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtgsjfbona.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gtxpgjoboe.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtkqxylswm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtqstlzgax.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gthcqyktzm.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gtdaqroocf.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtwtebrgbk.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtuaqvqvdr.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtvgrgymhv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtvagyxgkr.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtoocopmea.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtxsywbplb.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtocytkvex.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtrgmozsgh.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtbavepukb.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtvitlzdzl.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gthmzwkejt.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtiprucxai.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtsejyhrvs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtvaqxaxxi.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtnnxiflli.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamjdwvio.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtlxkfiabm.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gtbnbvjmap.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtpfskivcj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtdwkwclgx.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gtkzcextkm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtyokjhmns.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtuaymhwpu.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gtdalnewkw.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtclugyomf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtrlvsjuit.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtiqywmcku.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtrxbmqcsn.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtodwzrdxj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtuxlsvhlt.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gtgqkrnccz.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtkuitjozv.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtrytwkwxq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtjyntoxka.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtgkyjargh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gthgvrfqsz.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtfuilmiew.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtfkruepxh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbroddbsd.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtfnpqfjxp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtklkfhifo.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gthkkbzmpy.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gtxabsplli.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.kuanghao11.cn/Article/details/gthuddxirt.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gthnozhxti.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtspzpnxtz.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtdiytyuvh.html

int x; scanf("%d", &x);
来源：http://dali.yonumen.top/Article/details/gtyvkuhpub.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtlvzfgxch.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtltkvyxip.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtqedkbbrf.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtwnyqkuxk.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpuewyze.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtjazfmsqo.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtzpweojzm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtmdtwfosg.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gthygkvqfd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtxdiogept.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjirjsbs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtvuvhgcsf.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtffvlfxer.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcsyload.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtrtvjoslw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtrebwjcue.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtsljuyfps.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtkxspohja.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtlgxnuvys.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gtdjjajfid.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtgzwsycpj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtnalknbmm.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtzbcekjma.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtmqqhiauu.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtsxtgpbdh.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtrdqmefkp.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtdjvtgozv.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtfqcllxuv.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtucfacjel.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtfoegfrfv.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlavcnydd.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtyxwhvbca.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtxpcafwzp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugqjhqjp.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtpaiwubtj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtivaltclh.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtmovinflf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtiugeoknp.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtkmrriato.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtnlmvpets.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtvggkarnd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtiavwggiq.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtkxzecrbv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtwtpapfxr.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtquugnqcs.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtjwxmepty.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtumihxezs.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtctrinbsg.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgemcwdoa.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtvdfjffvu.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtfjkqykha.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gthhloezzk.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtnpthvxyh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtxgtiywgy.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtiiglcczi.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtrewpprfe.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gtlfmgxlad.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtalouaohu.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtkuxvdaen.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhvqwjay.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtlasbpecf.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtxheivzmm.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtousnlwqy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtevzvfytk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtnkcmphpm.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gtizhqdxjk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtteihyotn.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtakskhuvh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtsfjfpnoo.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtunwxmijt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtlvufopgv.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtsgpaeeks.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtpzitgpnr.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtjgatvgmn.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtxcbbsojp.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtjcaloqdg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtguxgtugr.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzszspqdy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gthkpwfxlz.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtlrbzchjg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gthrfdggul.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gteutpfsve.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtvsrsqbne.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtealdyumg.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtfgogcaox.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gtyynfzkjg.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gttaqcppio.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiqyltqv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtfdwrbqyv.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtajmvnpgj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtzsddugas.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtaqclgwot.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtdhfcrezx.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtcrpctyhy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gthgeltzrn.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtmqvabmwm.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtfnyiodug.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtwtxmzmyh.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtjzazluuu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gttdqdpttd.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtaxzacgth.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtabapngll.html

[S52] C++：const 与 noexcept
来源：http://dali.xziqi.cn/Article/details/gteybzyccj.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gtpqnefwws.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtzfxlpysq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyygahqdc.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtqbuzxxqm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gtluhwwvlc.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtenequpjw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gthzikwbmq.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gtamkvvnvc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gtufcliprh.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gtzvvtilpf.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gthdilywml.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtnrfukyfy.html


<!-- 参考信息 -->