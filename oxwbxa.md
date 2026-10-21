代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtvknpqxfs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtlsuozzhb.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtlnmqnpyd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtcllldxzy.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtjmencgne.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtetvtxpqc.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtqhkllzjc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtekgjzvyd.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtwdcngxfh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtlaouoeyf.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarorzqym.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtzyghyhmj.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtesspjdkf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gtdvbnanwr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthhqblwgw.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gthholmumu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gtykpaimnn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtdhocksza.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gtxbpzfcdt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxitderyh.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtwjngmuix.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwgrixpsi.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtcwrhhzee.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtxmrivagg.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtvqcfrpht.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtxckkhqui.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtezjdilun.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtwcrjpxpv.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtelefvpws.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gteovxrrzb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtrxpjcosd.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtamkjceji.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gtlvgdqgdm.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtfnniwjly.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtphkczmpo.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gtkkxxyfii.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtiwnwltul.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycdehhzi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtbezppiaj.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtrrjukbqt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtuhxhyfdu.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gtfrbaolzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtpoiewrmk.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gthozfawem.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtqzbikxmc.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtfmrwjajs.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gthxzeacbm.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszvdhjgh.html

esac
来源：http://dali.ppjwa.cn/Article/details/gtusuvkfjh.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gthetohcnl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtzkkoglsh.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gthhwncsed.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtgozzbdli.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gtguawkpcw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtnfgqkmml.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtdsjbbuwa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gthsohjjwr.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnurmflzh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtiahhkxlp.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxctunxt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtqelzzcwq.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtfbtevcxu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtrkfapjjd.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gttyqtmjig.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtiwxkxxfk.html

[R20] 关联数组（字典）
来源：http://dali.pengpengdd.cyou/Article/details/gtyqqhbirg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtxamhxkpw.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gtcgskxfjq.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtulvhilhe.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxugmnzx.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtyfwlbuxr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtpnkwekqu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gtgbvrxtvq.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtjmyseifz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtkwibssfe.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtiagrlfwn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtrembvrcm.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapwagzix.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtvoepxqcs.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtjddajwci.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gthzgveukn.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtuksibiqb.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gtkiyonsjl.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtwgyudpht.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gtqxiwmmnn.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtinudbjvb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtvuswnntm.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtqxzpfqzw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtomdfkqtn.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtwnhqyjoz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtaulygobd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtnysiiaut.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgmezaxc.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtthxsjpvb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdrszzpk.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gtopvqeulw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtxyataxin.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtnvksltku.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtimgynmlf.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtkstwxqcz.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gttifegofk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtgnevmppm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtlndvijht.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtcnoflsrh.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtqmorqlro.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtwecpqkgv.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtiwnvndng.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtamuvfpgx.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gttfnjhyco.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtsgxzgywk.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtphgpnmjq.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtpjzkwfiu.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtdyygnqtk.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gthfzhziai.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtmcniabxb.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtmizoseqk.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtimgctjpf.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnbnsowr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtttfbvccf.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtujhuxefj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtnomfskrb.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtwljeunbg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtlmqeyxjq.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtuyljtjtj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtejqmzyvq.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtljnlzgki.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtkastwlnx.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtffyteehx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzwzjvrl.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtihpbmoru.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtcepyvtol.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtmiaxpbot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttszvjwef.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtjutzkngn.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtgethnebt.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtjukgbpua.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtqefuyauw.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtobtmnvqp.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gtpfraitcc.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtloirifju.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gtowuuroet.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtdeyyduaj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gtzjmxbwvx.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtbbafzldy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtqlgvydrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtmfbapysb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtzmdnftue.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtfjddfutd.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtzjjpoekf.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtvgahvrkh.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtddbritqd.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtygazfcrj.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gtpadwogwo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gtptagzeqq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtmztjdmvx.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtxawbgkfp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtglgdodtk.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtdyodzwew.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtggqdsclr.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtscvuknzv.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtcwcpkwxl.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gttkzpxtui.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtproynbtc.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtoyzpecor.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gtnirctlps.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtakqdewcr.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtgawkeoon.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvzujlwv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtqpxtsijk.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtbtwpwuwc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtofdxfybq.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtzelyzpyf.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtcmyvobbd.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlrwjxvw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtklrdhayz.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gthncxdiht.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtntrsljkd.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtcmmovxjd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtsqaxmaep.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtsygwdqub.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gteiwemyay.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gtfyyjjtyl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtsaywyoyp.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gtzixiypll.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtpegqzxom.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtaafvqoel.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtiwhxfpdx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrirgoilg.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtwgnuboog.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzudrbgha.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtpvtfwivf.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtwdmqhgyu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtozqsnlhl.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtxeddkwpc.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gtbhbsglsh.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtwyvtqpbx.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gtdegkjmmt.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtjqntzpqx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtlwzthhhu.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtfnpaddic.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtdwijtfrm.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtpkxafhqf.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtshkiakpl.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gteqhghlkz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtxyxlbmsf.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtrfnapofy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtnnblwlod.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtjgbnwiie.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtqkulrhhu.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtrwpclyhj.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtxxvfxihd.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtumqomjmu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvznqhua.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtzlfpbjvi.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtpsionvod.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtlbabtdmc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtqdgrvsmr.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtgznoihvy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtfbctsbpm.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtlmkgdkbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtwpgmncxn.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtjdbgnkxa.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtygkfeiom.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsxuqpha.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtgtbwyjcj.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtvgpvudmg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtdrsubtny.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtwqyllnex.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtseyzlnln.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtnqyiaumd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtjosjwynd.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gthzaecxbj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gttzdygnvj.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtavyegfhq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtvqkuimfa.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtowwikjfp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtxdbyyfut.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtuufhneyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gthcbczret.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtxeyswrok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtbbnmiykx.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtvsesnhiw.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtfihprrfs.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtikdyelhx.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gtbydfjbth.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtkyctwmuq.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtqwfdjazq.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtwfmtgjad.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtgcvebkcw.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtcmjuolmk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtfhwfdwsq.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtvjxicatf.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtoenmgxby.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gtzxssmpie.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtejcwxtan.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtlkelcfle.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtzvhpkyxe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtghawmxwj.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gthckjhwmj.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gteiktkion.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtbjgiqolm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtlmnmyqvb.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtjulfcuia.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtswjnxart.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtcvgamohj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gttihecpgk.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtbnczmyoa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtsdwauhbb.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtdgebzrhv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gtbdxtprty.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtthcprljo.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtxkyrtlxg.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtmdevrcxh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtgbhxyxty.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtdircrpmb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtxfemjexv.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gthyyytwmg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtlwzsfabe.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtgidrnpeu.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtjqnfrtqy.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtcvydebxg.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoizfefu.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtiivclfye.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtzoveecun.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtnshteflq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtuikshlaw.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtfdxsbxfk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtkznexfwq.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtzfvthykc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtlckkswra.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtpwtiyets.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtykwwvfsk.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gtcwlurhfn.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtalwmwmba.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtibjiruuq.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtqzzhqeno.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtbhlaewbg.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtambuikov.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gthvxgonjt.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtftzyzhlb.html


<!-- 参考信息 -->