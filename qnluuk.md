代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gt2tarmxeev.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqmhwqau.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gt2leqnpprc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smkexpgz.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gt2azhoxiqh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gt2lstzqmpb.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gt2ilrzxnwh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gt2ekwfzvuk.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2dwvfegab.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gt2dgbbyyzd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2mhtczpfr.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2twxdlamj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2frxmyjqp.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gt2ijzvmkwz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gt2whjblava.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dqxdwgcp.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opzvruwx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tavhenld.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gt2nfoslbtf.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2dqmkhsei.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2tzkdixpn.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2owckhqkx.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2zbxkkzbl.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gt2keijgvdp.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2wbtvwvee.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gt2mgwqhwhx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhdgoxuc.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2meykcgoj.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnxtotin.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gt2xpcymayd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dpdnbyrt.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaqdxijm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2msuhamnd.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gt2dacwjpkw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gt2xlwbmlmv.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2kwqlodls.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2wizeuobf.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avdfetit.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gt2yytcrlfk.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gt2jiqaqbyg.html

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gt2psdvhdyg.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2sgkilvhe.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2nrdzpcwo.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2wljhewkb.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qruovgrw.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gt2syclnnju.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gt2ylkreisg.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gt2mcnvxpry.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2okjfsnvt.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2gdsfpjcc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2jlixxkmc.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2ozfsplvs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gt2wjzbidcz.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gt2illnbwtu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2rukuhxoo.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gt2ksybupsp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjmxzuvi.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2wrsmmwtx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gt2uavtaidr.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2cymwtwqt.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gt2mjvsynea.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gt2zlqlyhmj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ieqbeosi.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2zstadzqq.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gt2cedumqrc.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2uusxqqhc.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2njzqnwit.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2tpxnhjjq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gt2xmnvognf.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2cwyxgbmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gt2hjbaqqvp.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2svifhyvk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2luaalfuz.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gt2awkgtjof.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsrrtije.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gt2ehyndfpn.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gt2rlnwdwcv.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2pnfpdcfj.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gt2wcyxezqo.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gt2evprluov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gt2hzuqdwdx.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2fludozxd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gt2mftzvycj.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gt2rciynmrh.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gt2ghkkbyxn.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2mgrwpedi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gretzrjj.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuhldwsa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilhdluuo.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gt2ziosmepa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pknipqss.html

[R35] 后台执行并等待
来源：http://dali.yj20258.top/Article/details/gt2vohpquwv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2fketgmlu.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2yljtbnzn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gt2accjlszi.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2qkrlwfar.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gt2kbohaykw.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2hjxuahek.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2lckfessl.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gt2jftnvyvu.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2xcqsxdbz.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2fammcusg.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbqjuiuw.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gt2hlpffjan.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2ytkflmwj.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2buwbsyyw.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2ouanoedw.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2dxkyhsrj.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gt2ntjypchg.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gt2mzvdqavv.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gt2irawndou.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gt2vlqdaesv.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2lbgabxwx.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gt2dzdabiaf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gt2blnkxzxh.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2dtkfsxqs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2polaceln.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgbykqar.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2eeyrsvhq.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gt2zxgizmqy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbmptiiq.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gt2rjaxxumi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrtkwirp.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2hkncdbyk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gt2ulsnysxf.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2auxipwjn.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gt2sgmbbwln.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gt2npczkypn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gt2tgfuavwa.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gt2mfpeiwfw.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gt2abzjsmlp.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gt2zfyhgghx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpxzxhjz.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2weunzyrh.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gt2iptuxunp.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2qteudktl.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gt2qdcftyhh.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbqosksk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2hcfnwkkx.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmpniuwn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gt2zolzoqca.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2jqfhkuuc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2wtpgqxch.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbnvrtcq.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2nrevzsdn.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yiyispkq.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gt2unzbfcff.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gt2upukzhth.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxpsfyzm.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gt2pwznrqxy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gt2inxrowbx.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gt2hgdkeyxf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gt2wnxrloqy.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjemblop.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hiesxywp.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gt2aprimwbj.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2thcatbfz.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2rnvxmkmw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2hgjdqrfe.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gt2akukqyqp.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gt2sulljvax.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2zfkylaou.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2nxjxqcdk.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2bisilsvx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gt2cqnyhwyj.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gt2qwvtefgk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2wxgbyemq.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrltwmni.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2ipvvbyaf.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2byjrxauf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2tdmejbsb.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gt2tozgjeeh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gt2aktzngey.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkpziyfa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2xqtmwvju.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gt2zcaofidy.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gt2adytyshw.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gt2gwyrgpic.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gt2lkuesfvb.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2gjefrqgv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gt2upwbdqfx.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gt2tuscuryr.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gt2ribsoafs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2koljjids.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2lsmbbddw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fglwxsan.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2zufeirwl.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gt2ofluuohw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gt2pipsltjq.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2poxshbfi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gt2xyxtbmxs.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gt2awtkvaqw.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gt2khdakouj.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gt2vorrdenm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gt2rpnmvlwe.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gt2xvvffbxp.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2bjjxokjq.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2ghewbood.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2ybyztrcr.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gt2kwgsjyeh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2iickjiqx.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2oiajmwja.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gt2rhpuiroj.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gt2qpkjpxox.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2frjvvmdr.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gt2vrdbtewz.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2bbyipqnz.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2whvpskan.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gt2rorhlouk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykorwgae.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixefbarl.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gt2ltvtrwmh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhulwwjl.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gt2ypcemvlv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gt2vzrjxdef.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2uctdbrcb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gt2ftuysioz.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2txrwwwth.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2fbxuwjwe.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndvaahvl.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gt2iaxhjoal.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2kqcslslb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gt2kcidcppm.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfeivvag.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gt2swnhmwao.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2kijhindr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2kmztugla.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gt2wxtjewuc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2nwfxvxpt.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2bljreult.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2asbgmeum.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gt2jfaydyrd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gt2tidobwjh.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gt2sagvxmen.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gt2kqnlqcqm.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gt2lchhdjtz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gt2qqlezwth.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2oumtqvyt.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2lfjvwjlo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sswwegzr.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2tvygwbtj.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gt2gyheaifr.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqweuqmr.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2hqzbvuap.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfkminub.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gt2rxjszlvg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gt2othwqgpr.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilnaptaf.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2andfetuz.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2cmfpblfk.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gt2rygxbbwn.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2urldyyct.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gt2qepwwodt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gt2ujyrahtm.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2qvtgoals.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gt2krziying.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2fadhypfb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gt2xqldlbro.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gt2pvejgskj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gt2gsgymwcl.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gt2xpjvrgnr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2wgxlvfgm.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2egpmckpm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2cmysuvgr.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gt2ozhyrfvr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2flbgcaof.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmnmalll.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2eovicgdw.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gt2ykbduaae.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gt2osmikjls.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2jwxwnxef.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gt2jrqnzwup.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2yuzvqkrd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gt2qwzgnolx.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2ctoselig.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2dlycllbs.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gt2zzdhepcg.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gt2gmuenrea.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2brlclikc.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2aqqhchjb.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gt2itlsamog.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2vzderxac.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqazixcu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gt2kxkakbfi.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2zzokzovt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2ppmtzmel.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqvjanjg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxvawvfd.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2msoiowkg.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2dveusavx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utdbhmok.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gt2xqhhbezh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2jwlwical.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gt2jgcoatvt.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gt2vnwtogth.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gt2hfwetzso.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2wzkwlotn.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2jeopsoai.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gt2cxglahch.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2fyewuhti.html


<!-- 参考信息 -->